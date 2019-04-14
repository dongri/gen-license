# gen-licnese-rb

gen-license-rb is a 996.icu license generator implemented in Ruby, this generator is developed to generate various open-source licenses including MIT, Apache, etc. More importantly, the main purpose of this tool is to incorporate those aforesaid licenses into a brand new license: 996.icu, defined by 996.icu.

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
