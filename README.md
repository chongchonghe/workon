# Setup

In .zshrc

``` sh
source ~/tools/programs/workon/workon.rc
```

In .zshenv

```sh
# ~/tools: 'workon' and other programs
alias getdir="${HOME}/tools/programs/workon/getdir"
source ~/tools/programs/workon/workon.rc
export PATH=$PATH:~/tools/bin
```

