# op-work
Operator Work, 


## Chart1

### Test1
    - THis chart tried to use an initcontainer to copy in a new boostrap.
    ** This does not work.  No access to same file system.
    ** But then override the Startup command and injected our own bootstrap.sh


### Test2
    * Add a sidecar container.
    * Change new bootstrap to send data to /tmp/out
    * make sidecar cat the /tmp/out data


### Test3
    * Add pvc
    * removed init container, side car container
    * updated bootstrap to bring up engine




