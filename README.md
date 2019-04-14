# gen-licnese-rb

gen-license-rb is a license generator implemented in Ruby

# Install
```
$ gem install gen-license
```

# Usage
```
# Common LICENSE
gen-license mit # generate mit LICENSE file in current directory

# List LICENSE codes
gen-license --list

# Conmmon LICENSE with 996ICU
gen-license mit --996icu # generate mit LICENSE with 996ICU zh-cn version
gen-license mit --996icu en-us # generate mit LICENSE with 996ICU en-us version
```

### dev
```
$ gem build gen-license.gemspec
$ gem install gen-license-0.0.1.gem

$ gem push gen-license-0.0.1.gem
```
