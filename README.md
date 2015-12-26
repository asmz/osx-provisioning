# osx provisioning playbook

Inspired by https://github.com/shin1x1/osx-provisioning-with-ansible

## Requirements

* Xcode
* Homebrew
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
 
## Usage
 
```
$ git clone git@github.com:asmz/osx-provisioning.git
$ cd osx-provisioning
$ ansible-playbook -i hosts osx.yml
```

## Dependencies

* https://github.com/asmz/dotfiles (use `dotfiles` role )
