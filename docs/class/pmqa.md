
question 1:
```
de
The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ node -v
v18.12.0
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ git -v
Unknown option: -v
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ npm i docsify-cli -g
(⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠋ idealTree:lib: sill idealTree buildDeps
(⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠋ idealTree:lib: sill idealTree buildDeps
(⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠋ idealTree:lib: sill idealTree buildDeps
(⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠋ idealTree:lib: sill idealTree buildDeps
(⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂⠂) ⠋ idealTree:lib: sill idealTree buildDeps
npm ERR! code EACCES
npm ERR! syscall mkdir
npm ERR! path /usr/local/lib/node_modules/docsify-cli
npm ERR! errno -13
npm ERR! Error: EACCES: permission denied, mkdir '/usr/local/lib/node_modules/docsify-cli'
npm ERR!  [Error: EACCES: permission denied, mkdir '/usr/local/lib/node_modules/docsify-cli'] {
npm ERR!   errno: -13,
npm ERR!   code: 'EACCES',
npm ERR!   syscall: 'mkdir',
npm ERR!   path: '/usr/local/lib/node_modules/docsify-cli'
npm ERR! }
npm ERR! 
npm ERR! The operation was rejected by your operating system.
npm ERR! It is likely you do not have the permissions to access this file as the current user
npm ERR! 
npm ERR! If you believe this might be a permissions issue, please double-check the
npm ERR! permissions of the file and its containing directories, or try running
npm ERR! the command again as root/Administrator.

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/rabarisonandry/.npm/_logs/2022-11-09T04_12_20_454Z-debug-0.log
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ 
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ 
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ 
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ 
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ 
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ sudo chown -R $USER /usr/local/lib/node_modules
Password:
Sorry, try again.
Password:
RABARISONs-MacBook-Air:testdocsify rabarisonandry$ sudo npm i docsify-cli -g

added 205 packages, and audited 206 packages in 21s

16 packages are looking for funding
  run `npm fund` for details

7 vulnerabilities (6 moderate, 1 high)

To address issues that do not require attention, run:
  npm audit fix

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
RABARISONs-MacBook-Air:testdocsify rabarisonandry$  docsify init ./docs

Initialization succeeded! Please run docsify serve ./docs

RABARISONs-MacBook-Air:testdocsify rabarisonandry$  docsify serve docs
```



## reference
* [deal with premission](https://www.cnblogs.com/5idabaicai/p/16496270.html)