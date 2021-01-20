<div align="center">
  <h1 style="font-size: 200%;"><b>⚠️ THIS IS A WORK IN PROGRESS, DON'T TAKE IT TOO SERIOUSLY FOR NOW⚠️</b></h1>
</div>

# **General Information**

In this workshop, you will learn how to create a backend (that is the part of the application running on a server, managing the data) for an existing frontend (that is the user interface on a website, or a mobile phone).

Throughout the workshop we will be using Booster Framework, which is a new tool to create backends in an easier and faster way than most of the existing tools.

The instructors will assume basic knowledge of:

- Java or C++
- Command Line usage

**Who:** The course is aimed at students and juniors. **You don't need to have any previous knowledge of the tools that will be presented at the workshop.**

**Where: FIXME**

**When: FIXME**

**Requirements:**

- Participants must bring a laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. They should have a few specific software packages installed (listed below).
- It is required that you have a GitHub account (make sure that you share it in the pre-workshop survey)
- Join Discord?

Materials will be provided in advance of the workshop

**Contact:** Please email nick@booster.cloud or laia@booster.cloud for more information.

# **Code of Conduct**

Everyone who participates in this workshop is required to conform to the [Berlin Code of Conduct](https://berlincodeofconduct.org/). You can use the following link to report Code of Conduct incidents.

**INSERT TYPEFORM**

# **Surveys**

Please be sure to complete these surveys before and after the workshop.

Pre-workshop Survey

Post-workshop Survey

# Schedule

TBD

# **Setup**

To participate in the workshop, you will need access to the software described below. In addition, you will need an up-to-date web browser.

## Bash Shell (or equivalent)

- **Windows**
    - You will need to install WSL2 (Windows Subsystem for Linux), to do so, follow the following video (click on the image):

        [![thumbnail](https://img.youtube.com/vi/D7Em1wjMiak/0.jpg)](https://www.youtube.com/watch?v=D7Em1wjMiak)

    - After installing it like the steps in the video, you can use the `Ubuntu` application in order to use the Bash Shell.
    - To make sure that you get the latest versions of the packages that we will install, run `sudo apt update`
    - **From now on, use the console of the `Ubuntu` application**
- **MacOS and Linux**
    - You don't have to do anything, just open the terminal app

## Git

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on [github.com](https://github.com/). You will need a [supported web browser](https://help.github.com/articles/supported-browsers/).

You will need an account at [github.com](https://github.com/) for parts of the Git lesson. Basic GitHub accounts are free. We encourage you to create a GitHub account if you don't have one already.

- **Windows** and **Linux**
    - From the terminal, type `sudo apt install git` and press `Enter`
    - This will ask for your password.
        - ⚠️ It might look like you're not typing your password, but you are. The terminal just hides the characters so no one knows how many characters your password has.
    - Check that Git has been installed with `git --version`, the output should look like: `git version x.xx.x`
- **MacOS**
    - From the terminal, type `xcode-select --install` and press `Enter`
    - Check that Git has been installed with `git --version`,  the output should look like: `git version x.xx.x`

## Visual Studio Code

For writing the code, we will be using the free and open-source editor Visual Studio Code (not Visual Studio, but Visual Studio Code, note the **Code** in the end).

To install it, download the package from the [official website](https://code.visualstudio.com/), and install it following the steps that will appear on your screen.

## Node.js

Node.js is a code interpreter that let's you run JavaScript on your machine, instead of the browser. This is what Booster Framework uses. Node.js changes some things from version to version, so to install it, we will use a utility called **Node Version Manager (NVM)**, to make sure that everyone of us has the same version.

The installation steps are the same for all platforms. From your terminal app:

- Install NVM by typing the following command:
    - `curl -o- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh) | bash`
    - If that didn't work, try this one: `wget -qO- [https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh](https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh) | bash`
- Try running the `nvm` command now (type it in your terminal and press `Enter`)
    - If you get `nvm: command not found`, close your current terminal, open a new terminal, and try verifying again.
- Install Node.js by typing the following commands
    - `nvm install 12`
    - `nvm use 12`
    - `nvm alias default 12`
- Check that Node.js has been installed properly:
    - `node --version` should output `v12.xx.x`
    - `npm --version` should output `v6.xx.x`

## TypeScript

TypeScript is a language created by Microsoft, and the one that you use when working with Booster.

Don't worry! It is very similar to Java, and during the workshop we will give you an easy-peasy super-fast introduction to it, so you can start coding right away.

If you are super curious about it, you can always check the [official tutorial](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html).

To install TypeScript, from your console type:

- `npm install -g typescript`
    - If for some reason this command fails, try with `sudo npm install -g typescript`
- Check that it has been installed properly with `tsc --version`

## RimRaf

`rimraf` is a small utility that Booster uses underneath to maintain your project clean. To install it:

- `npm install -g rimraf`

## Booster Framework

To install Booster Framework, you have to type the following command:

- `npm install -g @boostercloud/cli`
- Check that it has been installed properly with `boost version`

## AWS Education Account

TBD - Should we just use the local provider?

## Starting Pack

We won't be creating the entire application from scratch, but instead, we will be creating a backend for a user interface, so you have to download the starting pack.

* First, enter the starting pack repo page, and make a fork:

  > Insert pictures of steps

* Then click on the green button, and copy the URL:

  > More pics

* Now, in a console, type the following commands:

  ```shell
  cd ~
  mkdir booster-workshop
  cd booster-workshop
  git clone <URL>
  cd <name of repo>
  ls
  ```

* This command should output something like this:

  ```shell
  ...
  ```

# Congratulations! 🎉

You are ready for the workshop! Can't wait to meet you! 😊