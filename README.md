# MAAS-on-Multipass
This is repository to learn and use Multipass, MAAS on LXD and all the commands you need

### To get started install Multipass on MacOS

### Open you command line 

```bash run_file.sh```

```multipass list```

###### Copy the IP for maas and open "http://<IP>:5240/MAAS/r/machines"

#### Multipass commands

```multipass launch --name foo```

```multipass exec foo -- <ubuntu command>``` - Not really useful imo

```multipass stop foo```

```multipass start foo```

```multipass delete --purge foo```

```multipass delete --purge --all```