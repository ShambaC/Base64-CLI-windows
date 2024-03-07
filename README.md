# Base64 CLI windows
 A CLI tool to encode decode strings into Base64 for windows

## Why
One day I was looking for some command for windows that I can use to encode and decode a string to and from base64. And I did find some, but they all needed me to write some complex stuff just to do this. And I wanted a offline tool because its too much work to open up a browser and go to some site. Thus I made this.

> [!TIP] 
> Its totally my original stuff, not stolen at all

<details>
<summary>Stolen Stuff</summary>

- [Encode function](http://web.mit.edu/freebsd/head/contrib/wpa/src/utils/base64.c) by Jouni Malinen, edited by GaspardP
- [Decode function](https://stackoverflow.com/a/37109258/22601798) by Polfosol

These were compiled and compared by GasperdP to provide the best soultion [here](https://stackoverflow.com/a/41094722/22601798)

</details>

## How to use
compile the cpp program or use the provided exe to run the command. <i>I am not a smelly nerd!</i>

```
// compile
g++ base64.cpp -o base64
```

Run in terminal
```
base64 [encode/decode/-e/-d] <String>
```