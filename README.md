Bash Script to Download Youtube URLs with bash on Linux
=


**Spanish** 
* copiar el archivo  **percentdecode.perl** y **youtube.sh**  en **/usr/local/bin** o habilitar path que el usuario pueda resolver
* dar permiso de ejecucion a ambos archivos 


**English**
* Copy and Paste file **percentdecode.perl** and **youtube.sh** to **/usr/local/bin** and give execution permssions


HELP
=
```bash
    Usage: youtube.sh [-kahs] URL|KEY
    Download youtube videos or audio using a URL or Video ID 

       -k          Use a Video ID
       -a      Download an audio file
       -s      Force https
       -h          This help
    section "Examples"
    echo -e "Usage with url to get video: youtube.sh  http://www.youtube.com/watch?v=OuSdU8tbcHY"
    echo -e "Usage with key to get video: youtube.sh  -k OuSdU8tbcHY "
    echo -e "Usage with key to get audio: youtube.sh  -k -a OuSdU8tbcHY"
    echo -e "Usage with url to get audio: youtube.sh  -a http://www.youtube.com/watch?v=OuSdU8tbcHY$"
    echo -e "This help: youtube.sh -h"
```
Enjoy !!!



