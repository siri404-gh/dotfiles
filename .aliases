#!/bin/bash
shopt -s expand_aliases

alias c='clear'
alias l='ls -lahG'
alias ls='ls --color=auto -G'
alias o='open .'
alias path='echo -e ${PATH//:/\\n}'

# Git
alias ga='git add'
alias gaa='git add --all'

alias gb='git branch'
alias gba='git branch -a'

alias gbd='git branch -d'
alias gbda='git branch --no-color --merged | command grep -vE "^(\*|\s*(master|develop|dev)\s*$)" | comma
nd xargs -n 1 git branch -d'

alias gcan='git commit --amend --no-edit'
alias gcar='git commit --amend --reset-author'

alias gce='git config --edit'
alias gceg='git config --edit --global'

alias gco='git checkout'
alias gcob='git checkout -b'
alias gcod='git checkout develop'
alias gcom='git checkout master'

alias gd='git diff'

alias gf='git fetch'

alias gl='git log'
alias glg='git log --graph'
alias gls='git log --stat'
alias glps='git log -p --stat'
alias gladg='git log --all --decorate --graph'
alias glgb='git log --graph --max-count=10'
alias gldo='git log --decorate --oneline'
alias gldgo='git log --decorate --graph --oneline'
alias gladgo='git log --all --decorate --graph --oneline'
alias glog='git log --graph --pretty='\''%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue
)<%an>%Creset'\'' --abbrev-commit'
alias gloga='git log --graph --pretty='\''%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blu
e)<%an>%Creset'\'' --abbrev-commit --all'
alias glp='_git_log_prettily'

alias gp='git push'
alias gpf='git push -f'
alias gpl='git pull'

alias gs='git status'
