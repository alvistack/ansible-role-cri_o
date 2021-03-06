# Ansible Role for CRI-O

## 4.7.0 - TBC

### Major Changes

  - Support CentOS 8 Stream
  - Support openSUSE Tumbleweed
  - Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

  - Simplify Molecule scenario for vagrant-libvirt
  - Migrate from Travis CI to GitLab CI
  - Support Fedora 33
  - Remove Fedora 32 support
  - Support Ubuntu 20.10
  - Remove redundant tags from tasks
  - Bugfix graceful shutdown deadlock due to systemd dependencies

## 4.5.0 - 2020-08-26

### Major Changes

  - Upgrade minimal Ansible Lint support to 4.3.2
  - Shutdown CRI-O containers before shutting down the system
  - Upgrade Travis CI test as Ubuntu Focal based
  - Upgrade minimal Ansible support to 2.10.0
  - Support openSUSE Leap 15.2
  - Remove Ubuntu 19.10 support

## 4.4.0 - 2020-06-04

### Major Changes

  - Install bash completion
  - Install with static binary archive
  - Support `crun`
  - Support Fedora 32
  - Support Debian 10
  - `molecule -s default` with delegated to localhost
  - Change default log verbosity to `warn`

## 4.3.0 - 2020-04-22

### Major Changes

  - Template `molecule -s default` with dummy docker driver
  - Support CentOS/RHEL 8
  - Support Ubuntu 20.04
  - Remove Ubuntu 16.04 support
  - Upgrade minimal Molecule support to 3.0.2

## 4.2.0 - 2020-02-23

  - Ininitial release for Ansible 2.9 or higher
  - Support both Ubuntu 18.04/19.10 or RHEL/CentOS 7 or openSUSE Leap 15.1
