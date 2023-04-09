# bash_profile

```
alias ll='ls -l'
alias work='cd ~/Documents/work'
alias dev='npm run dev'
alias start='npm run start'
alias test='npm run test'
alias build='npm run build'
alias pwdcp="PWD=$(pwd) && echo 'pwd copied to clipboard => $PWD' && echo -n $PWD | pbcopy"
alias port="lsof -i -P -n | awk 'NR==1 || /:$1/' | grep $1"
```
