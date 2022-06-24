---
description: >-
  Before getting the bot to work, let's start off by checking some things from
  your list
---

# Prerequisites

### Requirements:

* [ ] Python, version 3.7+.
* [ ] Node.js.


## Python:

First of all, check if you have Python 3.6+ already installed by running `python3 --version` (if this does not work, try `python --version`).

It returns the following output:

```
Python 3.7.0
```

Or anything above, than you can go to the next step.

If it returns the following output:

```
python3: command not found
```

Then you need to install Python.

### Installing python on windows

The easiest way to install Python on Windows is to use the [Python for Windows installer](https://www.python.org/downloads/windows/).

When you install Python this way, you will see a checkbox at the bottom which says _Add Python 3.10.x to PATH._ **Make sure you check this box, it is extremely crucial!**

![](<.gitbook/assets/image (2) (1).png>) ![](<.gitbook/assets/image (4).png>)

Alternatively, you can download python from the Microsoft Store (do not recommend, it's an outdated version and not supported by the official developers).


Finally, you can download python using a Package Manager (e.g. [Chocolatey](https://chocolatey.org/)) by running the following command:


```
choco install python
```


### Installing python on MacOS

The easiest way to install Python 3.7+ on MacOS is to use the [Installer for Python](https://www.python.org/downloads/mac-osx/).

Once you landed on the download page, click on Latest Python3 release. Then, go to the end of the page and click the `macOS 64-bit universal2 installer` button.

Then, click the `Install` button until the installation is complete.

Then, to check if everything is working, run the following command:


```
python3 --version
```

If it returns the following output:


```
Python 3.7.0
```

Or anything above, than you can go to the next step.

You can also install Python on MacOS by using the [Homebrew](https://brew.sh/) package manager.

After installing Homebrew, run the following command:

```
brew install python@3.10
```

### Installing python on Linux

Python can be installed by using your package manager (e.g. [apt-get](https://www.debian.org/), [yum](https://www.yum.com/), [pacman](https://www.archlinux.org/), [zypper](https://www.opensuse.org/) etc.).

## NodeJS

NodeJS is a JavaScript runtime environment that is used to execute JavaScript code. It is needed to use playwright.

### Installing nodejs on Windows

You can download nodejs installer from the [nodejs website](https://nodejs.org/en/download/). Click the LTS version. This will download the latest stable version of nodejs.

To check if node installed successfully, type `node` on your terminal to make sure node.js is installed correctly. You should see something like this:


![](<.gitbook/assets/image (3).png>)

You can also install nodejs on Windows by using the [Chocolatey](https://chocolatey.org/) package manager.

After installing Chocolatey, run the following command:

```
choco install nodejs
```

### Installing nodejs on MacOS

You can download nodejs installer from the [nodejs website](https://nodejs.org/en/download/). Click the LTS version. This will download the latest stable version of nodejs.

To check if node installed successfully, type `node` on your terminal to make sure node.js is installed correctly. You should see something like this:

You can also install nodejs on MacOS by using the [Homebrew](https://brew.sh/) package manager.

After installing Homebrew, run the following command:


```
brew install nodejs
```

### Installing nodejs on Linux

Install nodejs by using your package manager (e.g. [apt-get](https://www.debian.org/), [yum](https://www.yum.com/), [pacman](https://www.archlinux.org/), [zypper](https://www.opensuse.org/) etc.).


Voila! You are done. :thumbsup:
