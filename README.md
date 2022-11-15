### Initial Setup
- One `Python` File/ `Node Js`
- One `Procfile` without Extensions
- One `requirements.txt` file with modules name and version
- one `runtime.txt` explaining which python/node to be installed in the cloud.

### Procfile
- <service_name> : <program> <path_to_the_program>
```console
fetch_service: python fetch_firebase_data.py
delete_service: python delete_firebase_data.py

```

### requirements.txt
```console
requests==2.25.1
firebase-admin==3.1.0
pathlib==1.0.1
fyers-apiv2==2.0.5
requests-html==0.10.0
pandas==0.25.1
```

### runtime.txt
```console
python-3.7.13
```