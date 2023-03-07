# dummy_project

get running
1. add the link to this gh repo to binderhub
1. in one terminal on jupyverse server get JKG running
    1. `cd cli`
    1. `python3 aiployer_parser.py`
1. in another terminal on jupyverse server startup ngrok to tunnel to internet
    1. `wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip`
    1. `unzip ngrok-stable-linux-amd64.zip`
    1. `./ngrok http 8889`
1. access API by copy-pasting the https url from ngrok and accessing it in the browser: `https://{https_ngrok_url}/housing_stats`
