# DiD (Docker in Docker CLI)

This command line tool will help you to create docker in docker container based on image docker:dind it supply main functionality the main purpose of doing so is to create a vagrant alike feeling for the developers who develop for docker or using docker and want isolated environment to work with, it is in a very early stage so you are welcome to develop and expand as much as you can but don't forget to share it back with the community.

## Install
```
curl https://raw.githubusercontent.com/mmahrous/did/master/did -o /usr/local/bin/did && chmod +x /usr/local/bin/did
```
tested on MacOS 10.12.6 and Ubuntu 16.04

### Create
```
did create {name}
```

### SSH
```
did ssh {name}
```

### snapshot
```
did snapshot {name}
```

### del
```
did del {name}
```

Developed by Mohamed Mahrous <m.mahrous.94@gmail.com>
