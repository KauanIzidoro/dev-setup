# JavaScript (Node) & TypeScript (Nest) Setup 

> Install `nvm` for Node.js version management

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

# or

wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
> In this step you should add the following code to your shell configuration file, usually located at ~/.bashrc or ~/.zshrc:

```bash
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
```

> Restart the shell:

```bash
source ~./bashrc 
# or 
source ~./zshrc
```

> Install the latest version of `NodeJS`:

```bash
nvm install node 
```
