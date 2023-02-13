# tankman-doc

## PR 
### create .gitmodules
```shell
mkdir "tankManProject"
vim .gitmodules
## write in
[submodule "tankman.js"]
    path = tankman.js
    url = git@github.com:curry-trooper/tankman.js.git
[submodule "test"]
    path = test
    url = git@github.com:curry-trooper/test.git
[submodule "app"]
    path = app
    url = git@github.com:curry-trooper/tankman-app.git
[submodule "cli"]
    path = cli
    url = git@github.com:curry-trooper/tankman-cli.git
[submodule "docs"]
    path = docs
    url = git@github.com:curry-trooper/tankman-doc.git

## wq
```
### clone repositories
```shell
git clone --recursive git@github.com:curry-trooper/tankman.js.git && 
git clone --recursive git@github.com:curry-trooper/test.git && 
git clone --recursive git@github.com:curry-trooper/tankman-app.git &&
git clone --recursive git@github.com:curry-trooper/tankman-cli.git &&
git clone --recursive git@github.com:curry-trooper/tankman-doc.git &&
echo "welcome tankMan!"

```
