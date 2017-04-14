### 1. Setup VS Code for golang

* Install golang and set PATH. Reboot
* Copy .vscode 
* Install go extension
* Set git proxy:
```
    git config --global http.proxy http://127.0.0.1:1080
```
* Install `delve` [Debug Doc](https://github.com/Microsoft/vscode-go/wiki/Debugging-Go-code-using-VS-Code)
* While installing go libraries, you need to clean the src package if the last installation fails. 
Or you can download all the needed packages mannually and put it  in the GOPATH/src, then restart VS Code, it
should start to install the missing package automatically. 

### 2. VS Code Extensions
* C/C++
* C/C++ Clang command adapter
* C++ intellisense
* Code runner
* Docker
* Go
* Material Theme
* Python
* Vim
* vscode-icons

