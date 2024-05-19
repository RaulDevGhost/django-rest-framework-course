# 🚀🔥 Django Rest Framework (DRF) Course 🔥🚀

Welcome to this full Django Rest Framework (DRF) course. This course is perfect if you are looking to learn DRF and build your own API application. 🎓📚

---

## 📚 Prerequisites 📚

- Python >= 3.10 🐍

## 📝 Considerations 📝

I have added optional Docker containers 🐳 to simplify the build. If you want to use the Docker build, you should install Docker and Docker Compose on your local machine.

We will be calling our API throughout the next 8 modules. I have written the requests in Curl 🌀 and Httpie 📟.

Httpie provides a clean terminal output which is handy for this type of project. You will need to install it locally if you want to use the commands.

> 📌 Note: Httpie is pre-installed in the Docker container.

---

## 🎯 Getting started 🎯

First, you will need to clone down the first module.

1. Create a new directory on your local machine. I have called mine `drf_course`. This is your 'root directory'. 📁
2. Open a terminal and `cd` into the root directory. 🖥️
3. You can now clone the first module. You can do this a few different ways. I use SSH... 🔑

```bash
#option 1 - SSH
git clone --module_1 basics git@github.com:bobby-didcoding/drf_course.git .

#option 2 - Github CLI
gh repo clone bobby-didcoding/drf_course .
git checkout module_1

#option 3 - HTTPS
git clone --branch module_1 https://github.com/bobby-didcoding/drf_course.git .
