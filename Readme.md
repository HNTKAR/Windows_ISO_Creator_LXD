# 各種規定値
|パラメータ|値|
|:-:|:-:|
|利用イメージ|ubuntu-minimal:j|

# Windows iso のLXD対応化
```sh
ISO=/path/to/iso
lxc file push -p --mode "0777" $ISO CreateISO/
lxc exec CreateISO create
```

# 各種PATH
- distrobuilder  
  `/distrobuilder`
