# nodejsremover

Safely remove Node.js and NPM from OS X and Linux regardless of the installation method.
Logs all files and folders for removal to stdout and prompts the user for removal
confirmation.

## Usage

> For your own safety always check shell files before you run them from the internet [https://raw.githubusercontent.com/psyrendust/nodejsremover/master/nodejsremover](https://raw.githubusercontent.com/psyrendust/nodejsremover/master/nodejsremover).

**1. Using cURL**

```shell
curl -sSL https://raw.githubusercontent.com/psyrendust/nodejsremover/master/nodejsremover | bash
```

**2. Using Wget**

```shell
wget -qO- https://raw.githubusercontent.com/psyrendust/nodejsremover/master/nodejsremover | bash
```

## Node.js Installation Types

The following methods are used to install Node.js on OS X and Linux.

**1. Homebrew**

```shell
brew install node
```

**2. Node Version Manager**

```shell
curl https://raw.githubusercontent.com/creationix/nvm/v0.22.2/install.sh | bash
nvm install stable
nvm alias default stable
```

**3. 1-Click Installer from nodejs.org**

1. Visit: http://nodejs.org/
2. Click `INSTALL` button
3. Run the installer
