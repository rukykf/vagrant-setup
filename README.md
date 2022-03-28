### Start The Vagrant Machine

```
vagrant up
```

### Log into the machine
```
vagrant ssh
```

### Log out of the machine
```
Ctrl + D
```
or
```
Command + D
```
Try both, not sure which one will work on a Mac anymore.

### To stop (shut down) the running vagrant machine
```
vagrant halt
```
Run `vagrant halt` after logging out of a vagrant box in order to stop or shut down the machine.
After shutting down, whenever you want to start the machine again, use `vagrant up`

### Delete the machine
If the Vagrant box is giving issues, it's easier to just destroy with `vagrant destroy` and start it up again with `vagrant up`
```
vagrant destroy
```

### Note about running multiple vagrant machines
Try to avoid running more than one vagrant machine at the same time, this will quickly start eating up your computer resources. Instead shut down one machine before trying to start another. Whenever you run `vagrant up` in one folder, you've started a vagrant machine. If you were to `vagrant up` in a different folder with a different `Vagrantfile` then, that would be you starting another different vagrant machine. Like I mentioned, if you have to use more than one vagrant machine, shut one down before starting the other.
