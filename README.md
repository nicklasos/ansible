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
./deploy inventory
```

With optional tags
```
./deploy inventory --tags=site
```

Ping server
```
chmod +x ping
./ping inventory
```

