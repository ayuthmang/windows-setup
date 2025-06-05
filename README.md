# windows-setup

My Windows setup

## Essential Softwares Before Going Fotward

1. Install Chocolatey (https://chocolatey.org/install):
   Then open Powershell as administrator privilege and install the following packages:
   1. Install essential packages:
      ```sh
      $ choco install -y brave discord docker-desktop powershell-core processhacker telegram notion
      ```
   2. Dev essential packages:
      ```sh
      $ choco install -y git gitkraken vscode postman nvm
      ```

2. Install [scoop](https://scoop.sh/):
   ```sh
   $ Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   $ Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
   ```

4. Install OpenSSH and config 1Password

- Install OpenSSH on Windows: https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=gui
- Config 1Password for Windows: https://developer.1password.com/docs/ssh/agent/



## Essential global Node.js packages

```sh
$ npm install -g pnpm yarn ts-node nodemon
```
