# Getting started

First ensure vagrant and virtualbox are installed.

You'll need the hosts updater plugin.

```bash
vagrant plugin install vagrant-hostsupdater
```

Then start the python vm with

```bash
vagrant up
```

To access the the VM

```bash
vagrant ssh
```

then move to the vagrant directory

```bash
cd /vagrant
```

and setup your python environment with

```bash
virtualenv venv
```

Then every time you want to start developing type to setup python
```
. venv/bin/activate
```

and run your python script with

```bash
python yourscript.py
```

Any changes you make will be syncd to the vagrant directory on the VM automatically.
