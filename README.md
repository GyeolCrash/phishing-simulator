# phishing-simulator


## Description
* This project is designed in the Department of Software at Soongsil University
* The project aims to enhacne the public's ability to handle voice phishing


## Element
* app-client : Android Application for Clent
* gateway    : API Server between app-client and llm server
* llm        : llm server for LLM attacker

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

