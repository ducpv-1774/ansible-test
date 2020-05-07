# Role: ruby-with-rvm

### Tasks file
- [x] main.yml file
- [x] rvm.yml file
- [x] rubies.yml file

### After complete tasks
- Check rvm version on deploy user
```
$ ~./rvm/bin/rvm version
rvm 1.29.10 (latest) by Michal Papis, Piotr Kuczynski, Wayne E. Seguin [https://rvm.io]
```
- Check ruby version on deploy user
```
$ .rvm/bin/rvm alias list default
default => ruby-2.6.3
```
- Check bundler version
```
$ bundle -v
Bundler version 2.0.2
```
 
