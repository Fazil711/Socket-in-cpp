# TCP/IP server-client

This program is made using c++ library ws2tcpip.h and gcc compiler version 11.1.2 in codeblocks

It is just a traditional end-2-end socket for understanding in depth about the networking model

### Description

if you are using microsoft VScode then there won't be any problem but if you are using codeblocks or other platform using gcc compiler then the program won't work as `inet_ntop()` func isn't defined in vast versions of gcc thus you will need either vscode or gcc version 11 and integrate it with codeblocks or whatever platform 
and you should also install a terminal emulator PuTTY for testing the connections

running the `single.cpp` program would give this as an output:
![output1](https://user-images.githubusercontent.com/44942652/138149509-daa939be-aad2-4785-81da-4abf3452afc4.PNG)

But before that we need to set the PuTTY too:

![puttyset](https://user-images.githubusercontent.com/44942652/138149638-3d7b6049-11f1-4714-867f-e4d234ffc686.PNG)

but if we want to connect multiple clients
then using `multipleclient.cpp` we can have this out put:

![output2](https://user-images.githubusercontent.com/44942652/138149773-73992303-1d2b-4534-bc9c-cce20c19e38a.PNG)

#### &#128161; Techs & Tools
![](https://img.shields.io/badge/TextEditor-CodeBlocks-informational?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+QysrPC90aXRsZT48cGF0aCBkPSJNMjIuMzk0IDZjLS4xNjctLjI5LS4zOTgtLjU0My0uNjUyLS42OUwxMi45MjYuMjJjLS41MDktLjI5NC0xLjM0LS4yOTQtMS44NDggMEwyLjI2IDUuMzFjLS41MDguMjkzLS45MjMgMS4wMTMtLjkyMyAxLjZ2MTAuMThjMCAuMjk0LjEwNC42Mi4yNzEuOTEuMTY3LjI5LjM5OC41NDMuNjUyLjY5bDguODE2IDUuMDljLjUwOC4yOTMgMS4zNC4yOTMgMS44NDggMGw4LjgxNi01LjA5Yy4yNTQtLjE0Ny40ODUtLjQuNjUyLS42OS4xNjctLjI5LjI3LS42MTYuMjctLjkxVjYuOTFjLjAwMy0uMjk0LS4xLS42Mi0uMjY4LS45MXpNMTIgMTkuMTFjLTMuOTIgMC03LjEwOS0zLjE5LTcuMTA5LTcuMTEgMC0zLjkyIDMuMTktNy4xMSA3LjExLTcuMTFhNy4xMzMgNy4xMzMgMCAwMTYuMTU2IDMuNTUzbC0zLjA3NiAxLjc4YTMuNTY3IDMuNTY3IDAgMDAtMy4wOC0xLjc4QTMuNTYgMy41NiAwIDAwOC40NDQgMTIgMy41NiAzLjU2IDAgMDAxMiAxNS41NTVhMy41NyAzLjU3IDAgMDAzLjA4LTEuNzc4bDMuMDc4IDEuNzhBNy4xMzUgNy4xMzUgMCAwMTEyIDE5LjExem03LjExLTYuNzE1aC0uNzl2Ljc5aC0uNzl2LS43OWgtLjc5di0uNzloLjc5di0uNzloLjc5di43OWguNzl6bTIuOTYyIDBoLS43OXYuNzloLS43OXYtLjc5aC0uNzl2LS43OWguNzl2LS43OWguNzl2Ljc5aC43OXoiLz48L3N2Zz4=)
![](https://img.shields.io/badge/Code-C++-informational?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+QysrPC90aXRsZT48cGF0aCBkPSJNMjIuMzk0IDZjLS4xNjctLjI5LS4zOTgtLjU0My0uNjUyLS42OUwxMi45MjYuMjJjLS41MDktLjI5NC0xLjM0LS4yOTQtMS44NDggMEwyLjI2IDUuMzFjLS41MDguMjkzLS45MjMgMS4wMTMtLjkyMyAxLjZ2MTAuMThjMCAuMjk0LjEwNC42Mi4yNzEuOTEuMTY3LjI5LjM5OC41NDMuNjUyLjY5bDguODE2IDUuMDljLjUwOC4yOTMgMS4zNC4yOTMgMS44NDggMGw4LjgxNi01LjA5Yy4yNTQtLjE0Ny40ODUtLjQuNjUyLS42OS4xNjctLjI5LjI3LS42MTYuMjctLjkxVjYuOTFjLjAwMy0uMjk0LS4xLS42Mi0uMjY4LS45MXpNMTIgMTkuMTFjLTMuOTIgMC03LjEwOS0zLjE5LTcuMTA5LTcuMTEgMC0zLjkyIDMuMTktNy4xMSA3LjExLTcuMTFhNy4xMzMgNy4xMzMgMCAwMTYuMTU2IDMuNTUzbC0zLjA3NiAxLjc4YTMuNTY3IDMuNTY3IDAgMDAtMy4wOC0xLjc4QTMuNTYgMy41NiAwIDAwOC40NDQgMTIgMy41NiAzLjU2IDAgMDAxMiAxNS41NTVhMy41NyAzLjU3IDAgMDAzLjA4LTEuNzc4bDMuMDc4IDEuNzhBNy4xMzUgNy4xMzUgMCAwMTEyIDE5LjExem03LjExLTYuNzE1aC0uNzl2Ljc5aC0uNzl2LS43OWgtLjc5di0uNzloLjc5di0uNzloLjc5di43OWguNzl6bTIuOTYyIDBoLS43OXYuNzloLS43OXYtLjc5aC0uNzl2LS43OWguNzl2LS43OWguNzl2Ljc5aC43OXoiLz48L3N2Zz4=)

![](https://img.shields.io/badge/Library-ws2tcpip.h-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Library-sstream-informational?style=flat&logo=<LOGO_NAME>&logoColor=white&color=2bbc8a)