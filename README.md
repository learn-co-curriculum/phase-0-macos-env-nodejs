# Mac NodeJS Install

## Install Node Version Manager (NVM)

[Node Version Manager (NVM)][nvm] is a tool that will allow you to download and install
multiple versions of Node.js, one of the environments for the JavaScript
programming language that we teach at Flatiron School. Installing NVM is the
first step in installing Node.js on your macOS operating system.

[nvm]: https://github.com/nvm-sh/nvm

### Action Item

1. Open the "Terminal" application using "Spotlight Search"
2. Type `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | zsh` and press `<Enter>`
3. Close the "Terminal" application
4. Reopen the "Terminal" application using "Spotlight Search"
5. Type `nvm` and press `<Enter>`

### Check Your Work

<iframe width="560" height="315" src="https://www.youtube.com/embed/jllJ7ajjRkA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you see a message ending with "Note: to remove, delete, or uninstall nvm",
continue below.

## Install Node.js

For our JavaScript labs and lessons, we expect that students use
[Node.js][node] on their macOS operating system. If Node Version Manager (NVM)
has been successfully installed, you can quickly install Node.js with a couple
of commands.

[node]: https://nodejs.org/en/

### Action Item

1. Open the "Terminal" application using "Spotlight Search"
2. Type `nvm install --lts` and press `<Enter>`
3. Type `nvm list` and press `<Enter>`

### Check Your Work

<iframe width="560" height="315" src="https://www.youtube.com/embed/NzWGzrBPRVI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you see a message starting with "-> v14.13.0" (or any higher number, like "->
v14.13.10" or "-> v16.10.0"), continue to the next lesson, **Installing Ruby on
macOS**.
