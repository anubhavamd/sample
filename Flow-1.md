```mermaid
flowchart LR
    Inferencing-->MIGraphX-Introduction
    MIGraphX-Introduction-->MIGraphX-Installation
    MIGraphX-Installation--> Install-Binaries
    MIGraphX-Installation--> Building-from-source
    MIGraphX-Installation--> Docker
    Install-Binaries --> MIGraphX-Example
    Building-from-source --> MIGraphX-Example
    Docker --> MIGraphX-Example
    MIGraphX-Example--> MIGraphX-Python-API
    MIGraphX-Example--> MIGraphX-C++-API
    MIGraphX-Introduction--> Tuning-GraphX
    Tuning-GraphX --> Tuned
    Tuning-GraphX --> Untunned
    
    
    click Inferencing href "https://github.com/anubhavamd/Deep-Learning-Updated#51-inferencing"
    click MIGraphX-Introduction href "https://github.com/anubhavamd/Deep-Learning-Updated#511-migraphx-introduction"
    click MIGraphX-Installation href "https://github.com/anubhavamd/Deep-Learning-Updated#512-migraphx-installation"
    click Install-Binaries href "https://github.com/anubhavamd/Deep-Learning-Updated#5121-option-1-installing-binaries"
    click Building-from-source href "https://github.com/anubhavamd/Deep-Learning-Updated#5122-option-2-building-from-source"
    click Docker href "https://github.com/anubhavamd/Deep-Learning-Updated#5123-option-3-use-docker"
    
```
