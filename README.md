<div align="center">

![Numaan Opai terminal banner](banner.svg)

![Status](https://img.shields.io/badge/status-OPEN__TO__WORK-00ff41?style=for-the-badge&labelColor=0a0a0a)
![Level](https://img.shields.io/badge/level-entry--level-00e5ff?style=for-the-badge&labelColor=0a0a0a)
[![Portfolio](https://img.shields.io/badge/Portfolio-visit-00ff41?style=for-the-badge&labelColor=0a0a0a)](https://numaansportfolio.vercel.app/)

</div>

<br>

![01_about.sh](h01.svg)

![about](about.svg)

![boot log](bootlog.svg)

<br>

![02_roadmap](h02.svg)

![roadmap](roadmap.svg)

<br>

![03_stack_status](h03.svg)

![stack status](stack.svg)

**background tools I have used**

![Python](https://img.shields.io/badge/Python-0a0a0a?style=flat-square&logo=python&logoColor=00ff41)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0a0a0a?style=flat-square&logo=tensorflow&logoColor=00ff41)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0a0a0a?style=flat-square&logo=scikitlearn&logoColor=00ff41)
![Pandas](https://img.shields.io/badge/Pandas-0a0a0a?style=flat-square&logo=pandas&logoColor=00ff41)
![NumPy](https://img.shields.io/badge/NumPy-0a0a0a?style=flat-square&logo=numpy&logoColor=00ff41)
![Jupyter](https://img.shields.io/badge/Jupyter-0a0a0a?style=flat-square&logo=jupyter&logoColor=00ff41)
![React](https://img.shields.io/badge/React-0a0a0a?style=flat-square&logo=react&logoColor=00ff41)
![Next.js](https://img.shields.io/badge/Next.js-0a0a0a?style=flat-square&logo=nextdotjs&logoColor=00ff41)
![Node.js](https://img.shields.io/badge/Node.js-0a0a0a?style=flat-square&logo=nodedotjs&logoColor=00ff41)
![JavaScript](https://img.shields.io/badge/JavaScript-0a0a0a?style=flat-square&logo=javascript&logoColor=00ff41)
![HTML](https://img.shields.io/badge/HTML-0a0a0a?style=flat-square&logo=html5&logoColor=00ff41)
![CSS](https://img.shields.io/badge/CSS-0a0a0a?style=flat-square&logo=css3&logoColor=00ff41)
![Tailwind](https://img.shields.io/badge/Tailwind-0a0a0a?style=flat-square&logo=tailwindcss&logoColor=00ff41)
![Flutter](https://img.shields.io/badge/Flutter-0a0a0a?style=flat-square&logo=flutter&logoColor=00ff41)
![Dart](https://img.shields.io/badge/Dart-0a0a0a?style=flat-square&logo=dart&logoColor=00ff41)
![Java](https://img.shields.io/badge/Java-0a0a0a?style=flat-square&logo=openjdk&logoColor=00ff41)
![MongoDB](https://img.shields.io/badge/MongoDB-0a0a0a?style=flat-square&logo=mongodb&logoColor=00ff41)
![MySQL](https://img.shields.io/badge/MySQL-0a0a0a?style=flat-square&logo=mysql&logoColor=00ff41)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0a0a0a?style=flat-square&logo=postgresql&logoColor=00ff41)

<br>

![04_background](h04.svg)

![background](background.svg)

<br>

![05_featured_projects](h05.svg)

![featured projects](projects.svg)

<br>

![06_command_reference](h06.svg)

```bash
$ docker ps                  # list running containers
$ docker logs <container>    # read a container's logs
$ systemctl status nginx     # check whether a service is running
$ ss -lntp                   # listening TCP ports and their processes
$ git status                 # changed and staged files
```

<details>
<summary><b>lab log: docker basics on WSL Ubuntu</b> (real session from my own machine, click to expand)</summary>

```console
numaan@ubuntu:~/Linux$ docker run -it ubuntu bash
root@75d6eda7b846:/# docker ps -a
bash: docker: command not found
root@75d6eda7b846:/# exit

numaan@ubuntu:~/Linux$ docker start -ai wizardly_heisenberg
root@76d4545a1770:/# cat /etc/os-release
PRETTY_NAME="Ubuntu 26.04.1 LTS"
VERSION_ID="26.04"

numaan@ubuntu:~/Linux$ docker run -dit --name <name> ubuntu
484025e1c97c696b171c9e449b90169e000b07bba9ef92067cb3db3bfeadef24
numaan@ubuntu:~/Linux$ docker ps
CONTAINER ID   IMAGE     COMMAND       CREATED         STATUS
484025e1c97c   ubuntu    "/bin/bash"   2 minutes ago   Up 2 minutes
```

**what this taught me:** the docker CLI runs on the host, so `docker: command not found` inside the container is expected. A container stops when its main process exits, and `docker start -ai` reattaches. `-it` gives an interactive shell; `-dit` keeps it running in the background. Each image ships its own minimal userland.

</details>

<br>

![08_contact](h08.svg)

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-numaaannn-0a0a0a?style=for-the-badge&logo=github&logoColor=00ff41)](https://github.com/numaaannn)
[![Portfolio](https://img.shields.io/badge/Portfolio-numaansportfolio-0a0a0a?style=for-the-badge&logo=vercel&logoColor=00e5ff)](https://numaansportfolio.vercel.app/)
[![Email](https://img.shields.io/badge/Email-numaan.y.opai%40gmail.com-0a0a0a?style=for-the-badge&logo=gmail&logoColor=ffd866)](mailto:numaan.y.opai@gmail.com)

![exit](footer.svg)

</div>
