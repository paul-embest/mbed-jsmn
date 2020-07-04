# mbed-jsmn

This JSON library (jsmn) wrapper for ARM mbed. In this way, users could add this library to their mbed project easily.

jsmn (pronounced like ‘jasmine’) is a minimalistic JSON parser in C. It can be easily integrated into the resource-limited projects or embedded systems. More info about jsmn library, please refer to [zserge/jsmn](https://github.com/zserge/jsmn)


## What do I do

- Copy the jsmn.h file from [zserge/jsmn](https://github.com/zserge/jsmn) and rename as  zserge_jsmn.h
- Create a jsmn.c, this file will create the functions of jsmn symbols.
- Create a jsmn.h, this file will include the zeerge_jsmn.h but define a macro JSMN_HEADER to avoide to create jsmn function symbols again.
- Client just need to include the jsmn.h as the same


## How to use

### Add this library to mbed project

```bash
mbed add https://github.com/ahnniu/mbed-jsmn.git
```

### How to use in a mbed project

It's simple just include the jsmn.h

```
#include "jsmh.h"
```

### API

Refer to [zserge/jsmn](https://github.com/zserge/jsmn)


### How to upgrade to the latest mainline of jsmn

get the latest jsmn.h from manline and replace the zserge_jsmn.h

