# scientific-linux

Provisioning of core scientific software into a Linux VM.

## Start the virtual machine

```
vagrant up
```

## Provision the virtual machine with scientific software

```
cd provisioning
ansible-playbook -i hosts base.yml
```

## Base scientific system includes

### Text editors

- nano
- vim
- emacs

### Languages

- Development tools (gcc, g++, gfortran, make, automake, git, ...)
- Python
- Perl
- Ruby
- Java
- R

### Default Python packages

- pip
- virtualenv
- numpy
- scipy
- matplotlib
- ipython

### Development libraries

- atlas
- lapack
- blas
- gsl
- libpng
- zlib
- freetype
- freeimage
