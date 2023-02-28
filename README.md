# tankman-doc

## PR 
### create .gitmodules
```shell
mkdir "tankManProject"
vim .gitmodules
```
## write in
```shell
[submodule "tankman.js"]
    path = tankman.js
    url = git@github.com:curry-trooper/tankman.js.git
[submodule "app"]
    path = app
    url = git@github.com:curry-trooper/tankman-app.git
[submodule "cli"]
    path = cli
    url = git@github.com:curry-trooper/tankman-cli.git
[submodule "docs"]
    path = docs
    url = git@github.com:curry-trooper/tankman-doc.git
[submodule "tank-cache"]
    path = docs
    url = git@github.com:curry-trooper/tank-cache.git

## wq
```
### clone repositories
```shell
git clone --recursive git@github.com:curry-trooper/tankman.js.git && 
git clone --recursive git@github.com:curry-trooper/tankman-app.git &&
git clone --recursive git@github.com:curry-trooper/tankman-cli.git &&
git clone --recursive git@github.com:curry-trooper/tankman-doc.git &&
git clone --recursive git@github.com:curry-trooper/tank-cache.git &&
echo welcome tankMan!

```
