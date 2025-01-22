# .bash_profile

```
alias ll='ls -l'
alias work='cd ~/Documents/work'
alias dev='npm run dev'
alias start='npm run start'
alias test='npm run test'
alias build='npm run build'
alias pwd2="PWD=$(pwd) && echo 'pwd copied to clipboard => $PWD' && echo -n $PWD | pbcopy"
alias port='bash -c '\''PORT="$1" && lsof -i -P -n | awk "NR==1 || /:$PORT/" | awk "NR==1{print \$0;next}{print \$0 | \"grep --color=always $PORT\"}"'\'' -'
alias ws='open -a "webstorm"'
```


# pastebot
```
// docker通杀
docker stop $(docker ps -q) & docker rm $(docker ps -aq)

// 符号集
、·「」【】《》，。？；：“”￥
⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎ ⬇︎

// 淘宝npm
--registry https://registry.npm.taobao.org

```
