# Install
### Virtualenv + python
```
pip3 install virtualenv
./env/bin/pip install ansible
```
### Setup

Deploy
```
chmod +x deploy
./deploy inventory-name app-name
./deploy my-project app
```

With optional tags
```
./deploy inventory-name --tags=site
```

Ping server
```
chmod +x ping
./ping inventory
```

