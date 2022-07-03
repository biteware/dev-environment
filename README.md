# Development Environment
A repository holding my ansible scripts to setup my local environment. 

## Testing Steps
Included with the repository is a `Dockerfile` and a `Makefile` that can be used
to create a fresh Arch install and test the ansible install against the fresh
install. 

```shell
make build
make run

# within the image
ansible-playbook local.yml
```

## TODO
- [x] git setup
- [x] .ssh installation
- [ ] dotfile installation via stow
- [ ] local script installation
