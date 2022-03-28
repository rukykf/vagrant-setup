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
