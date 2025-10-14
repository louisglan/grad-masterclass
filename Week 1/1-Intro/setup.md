# 🏠Setup

## Chrome

Visit https://support.google.com/chrome/answer/95346?hl=en-GB&co=GENIE.Platform%3DDesktop#zippy= and follow the instructions

## **Git**

Visit https://github.com/ and log in/create a new account

Visit https://gitforwindows.org/

Proceed with install steps. If it asks for a default editor select VS Code

## **Docker**

Install docker desktop https://docs.docker.com/desktop/install/windows-install/ with recommended settings

Sign up to docker desktop

## **Frontend Masters**

Visit https://frontendmasters.com/bootcamp and sign up for a free account.

## **CodeCademy**

Visit https://www.codecademy.com/learn and sign up

## **VS Code**

Download VS Code from the Microsoft Store

Select extensions in the left panel

Install prettier and ESLint

Select File > Autosave (if there is not already a tick by autosave)

## **Notion**

Notion is blocked by EY on Windows laptops - if using Windows you are encouraged to use Markdown to take notes instead (see the [Markdown page](./markdown.md) for a cheatsheet)

Go to https://www.notion.so/ and create a new account

Tips:

- ‘/’ allows you to write commands
- Wrapping text in backticks (`) turns it into code
- You can get a code block by moving to a new line and typing “/code”

## **WSL (Window Subsystem for Linux)**

Most open source tools (e.g., Docker) are used for UNIX-based operating systems (Mac and Linux). In order to easily integrate with these tools easily we need to make sure WSL is set up:

Click in search bar

Search for “turn Windows features on or off”

Make sure “Virtual Machine Platform” and “Windows Subsystem for Linux” are enabled. If not, enable them

Restart your computer when prompted

Search for “command prompt”

Type in `wsl --status` and hit enter

Run `wsl --update`. Hit yes if it asks you anything

Search Microsoft store for “Ubuntu” and try and install it

Open it once it has installed

Create a unix username and password (lowercase username, password won’t show on screen as you type it)

Set Ubuntu as your default terminal in VS code:

1. Open VS Code
2. Press F1
3. Type `Terminal: Select Default Profile`
4. Select Ubuntu (WSL)

## **Postman**

Go to https://www.postman.com/downloads and download postman

Run the setup.exe

Continue without an account (unless you want to make one)

Open lightweight API client

## CodeWars

Go to https://www.codewars.com/ and create an account

Add yourself to the EYEngineers clan under account settings

Quick demo

## **Linux/Mac**

### ZSH

Zsh is a shell that has some nice features such as superior auto-completion. It is by no means essential

Run `zsh –version` to confirm pre-installation and `echo $SHELL` to confirm zsh is set to default shell

Run `sudo apt install zsh` if not already installed and type “y” when prompted
Run `chsh -s $(which zsh)` if zsh is not set to default shell

Restart computer

Open Ubuntu again

When prompted type in “2”

Now in VS code when you create a new terminal you can select Ubuntu (WSL). You may need to restart VS code if you haven’t already

### Homebrew

Go to https://brew.sh/ and follow instructions

Copy and paste the commands in “next steps”. Nothing will be logged to terminal but you will know if it worked if the next step (node) works

## Node

Open Ubuntu and run `brew install node` - this is the power of homebrew

## Mac Only

Install Rectangle app

[Back](links.md)