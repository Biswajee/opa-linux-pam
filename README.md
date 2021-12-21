# OPA Linux PAM module

The repository aims at replacing the Linux PAM module on Ubuntu with **OPA (Open Policy Agent)** for PAM
authentication. To achieve this, the changes are executed using pipeline steps on the `ubuntu-20.04` agent.

Below screenshot shows it can be acheived in a local system:

![screenshot](https://user-images.githubusercontent.com/26689027/146967728-af704dea-7df9-453e-911d-fd53e9e14a3c.png)

Please checkout the repository that spins up the remote authentication server [here](https://github.com/Biswajee/heroku-opa-server).

_The setup is a POC only and contains several security loopholes. Please do not use it for production._  
