# py-devops-passwd-manager


## Start server

```
$ python3 password.py
```

## Test

```
$ curl -k -X POST -F 'username=alice' -F 'password=myalicepassword' 'https://0.0.0.0:5000/singup/v1'
$ curl -k -X POST -F 'username=alice' -F 'password=myalicepassword' 'https://0.0.0.0:5000/login/v1'
```