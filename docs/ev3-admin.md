# EV3 Administration

## Connecting

The default username/password is: robot/maker

Connect to an EV3 named *ev3dev1.local* with:
```bash
$ ssh robot@ev3dev1.local
```

Copy files to an EV3 named *ev3dev1.local* with a `sftp` session:
```bash
$ sftp robot@ev3dev1.local
robot@ev3dev3.local's password: 
Connected to ev3dev3.local.
sftp> put file_name
```

Or you can use `scp`:
```bash
$ scp file_name robot@ev3dev1.local:/home/robot/
```


## Linux Update

```bash
$ sudo apt-get
```

## EV3 Python Bindings

Install the EV3 Python bindings with:
```bash
@ pip install python-ev3dev
```

For full documentation visit 
[here](https://github.com/rhempel/ev3dev-lang-python).