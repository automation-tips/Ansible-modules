# How to make password field

install python module

```
$ pip install passlib
```

How to make password hash

```
$ python -c "from passlib.hash import sha512_crypt; import getpass; print(sha512_crypt.using(rounds=5000).hash(getpass.getpass()))"
Password: [Enter Your password]
```
