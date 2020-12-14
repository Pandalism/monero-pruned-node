# monero-full-node

Docker image to run a monero full network node but with pruning enabled

### Synology Issues
If you are getting admin rights issues in Synology. SSH into the device and `sudo chown -id 1000 $dir`, with `$dir` being whatever directory the docker is pointed at for storing the data.

### Credit

All credit to the original dockerfile maker **kannix** and the original dockerfile, all I did was add an extra argument to the monerod executable.

[https://github.com/kannix/monero-full-node](https://github.com/kannix/monero-full-node)