# roonit
"roonit" is a simple tool for enabling and disabling services in runit (Void Linux).

## "Installing"
Pretty much just run `make`, then copy it to /usr/local/bin  
Requires GCC

## Usage
`roonit enable <service>` will enable a service located in /etc/sv/  
`roonit disable <service>` will remove a service in /var/service/

## TODO:
  - Figure out how to use `symlinkat()`
  - Figure out how to use `getopts()`
  - Figure out how to do a makefile install
  - Fix this garbage code
  - Properly learn the C programming language
