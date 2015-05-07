# ansible-jenkins

[Jenkins](https://jenkins-ci.org/) - An extensible open source continuous integration server

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

## Tunables
- `jenkins_user` (string) - The user Jenkins runs as.
- `jenkins_runtime_root` (string) - Where Jenkins will place PID files.
- `jenkins_pidfile_path` (string) - Where Jenkins will place its PID file.

## Dependencies
- [telusdigital.apt-repository](https://github.com/telusdigital/ansible-apt-repository/)
- [telusdigital.java](https://github.com/telusdigital/ansible-java/)
- [telusdigital.upstart](https://github.com/telusdigital/ansible-upstart/)

## Example Playbook
```
- hosts: servers
  roles:
    - role: telusdigital.jenkins
```

## License
[MIT](https://tldrlegal.com/license/mit-license)

## Contributors
- [Chris Olstrom](https://colstrom.github.io/) | [e-mail](mailto:chris@olstrom.com) | [Twitter](https://twitter.com/ChrisOlstrom)
- [Aaron Pederson](https://aaronpederson.github.io) | [e-mail](mailto:aaronpederson@gmail.com) | [Twitter](https://twitter.com/GunFuSamurai)
- [Justin Scott](https://jvscott.net) | [e-mail](mailto:jvscott@gmail.com) | [Twitter](https://twitter.com/AKindlyOrc)
