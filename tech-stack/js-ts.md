# JavaScript (Node) & TypeScript (Nest) Setup 

> Install `nvm` for Node.js version management

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

> With `wget`:

```bash 
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

### Start a `Node` project: 

> Create a new directory for your project:

```bash
mkdir <project_name>
cd <project_name>
```

> Initialize with `npm`:

```bash 
npm init -y
```

> Install `express` or `fastify`:

```bash
npm instalx express
# or  
npm install fastify 
```

> Setup `TypeScript` and tools:

```bash 
npm install typescript ts-node @types/node @types/express --save-dev
# or
npm install typescript ts-node @types/node @fastify/types-provider-typebox --save-dev
```

> Create a new file `tsconfig.json`:

```bash
npx tsc --init
```

> Run the server:

```bash 
npm run dev
```

### Start a `Nest` project: 

> Install the `Nest CLI`

```bash 
npm install -g @nestjs/cli
```
> Create a new project:

```bash 
nest new <project_name>
```
> Run the project:

```bash
npm run start:dev
```
