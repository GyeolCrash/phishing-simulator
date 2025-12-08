# phishing-simulator


## Description
* This project is designed in the Department of Software at Soongsil University.
* The project aims to enhacne the public's ability to handle voice phishing.


## Element
* app-client : Android application for Clent
* gateway    : API server between app-client and llm server
* llm        : LLM server for LLM attacker

## Directory
```bash
/app-client     (Android application repository submodule)
/gateway        (Gateway repository submodule)
/llm            (LLM server repository submodule)
```

## Clone
```bash
git clone https://github.com/GyeolCrash/phishing-simulator
git submodule update --init --recursive
```

