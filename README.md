---
title: "Debian update scripts"
subtitle: "Create an script that updates the system and set it up for daily execution to keep you server up to date"
tags: ["cybersecurity"]
authors: ["arnaldoperez"]

---

# Networking on VirtualBox

<!-- hide -->

> By [@arnaldoperez](https://github.com/arnaldoperez) and [other contributors](https://github.com/4GeeksAcademy/update-script-cron-task-debian/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

![last commit](https://img.shields.io/github/last-commit/4geeksacademy/installing-windows-on-virtual-machine)
[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*Estas instrucciones [están disponibles en 🇪🇸 español](https://github.com/4GeeksAcademy/update-script-cron-task-debian/blob/master/README.es.md)*
<!-- endhide -->

For this practice you must import a virtual machine that we have prepared for you. It comes with Debian installed and it has some basic settings that will be used along the bootcamp. Otherwise is a regular Debian machine like any other, and it will be an important space where you'll learn how to use GNU/Linux systems in a secure way for it use in network environments as a server.

[Download here](https://drive.google.com/file/d/1MiV1F_W9TWsP0saKF_IMTahSs4bwrFe7/view?usp=drive_link) the file that you must import to VirtualBox to create de Debian virtual machine. It is a heavy file, so it is advisable to download it in advance to save time when doing the practice.

> **Information to access the Debian machine**<br>
**User**: deb<br>
**Password**: 123456<br>
**RootPassword**: 123456

<!-- hide -->
## Before you start...

> We need you! These exercises are built and maintained in collaboration with contributors such as yourself. If you find any bugs or misspellings please contribute and/or report them.

<!-- endhide -->

## 🌱 How to start this project.

First fork the repo [4GeeksAcademy/update-script-cron-task-debian](https://github.com/4GeeksAcademy/update-script-cron-task-debian/fork). You'll need your own fork of this repo in order to deliver your results. After that you have a couple of options...

### One click installation (recommended):

Then you can open these exercises in just a few seconds by clicking `<> Code` and then `Create codespace`.

> Once you have VSCode open the LearnPack exercises should start automatically. If exercises don't run automatically, you can try typing on your terminal: `$ learnpack start`

### Local Installation

Clone this repository in your local environment and follow the steps below:

1. Install LearnPack, the package manager for learning tutorials and the node compiler plugin for learnpack, make sure you also have node.js 14:

```bash
$ npm i @learnpack/learnpack -g
$ learnpack plugins:install learnpack-node
```

2. Start the tutorial/exercises by running the following command at the same level where your learn.json file is:

```bash
$ npm i jest@24.8.0 -g
$ learnpack start
```


<!-- hide -->

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Arnaldo Perez (arnaloperez)](https://github.com/arnaloperez) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribution: (bug reports) 🐛

3. [Lorena Gubaira (lorenagubaira)](https://github.com/lorenagubaira), contribution: (bug reports) 🐛, contribution: (editor), (translation) 🌎

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind are welcome!

This and many other exercises are built by students as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sánchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and  [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning).You can alse deepdive in the world of cybersecurity with our [Cybersecurity Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/cybersecurity).
<!-- endhide -->