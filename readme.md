
progen_generate命令：

progen init -p LED -tar stm32f103rb

progen generate -f projects.yaml -p LED -t iar-arm

//加入RT-Thread内核
git submodule add https://github.com/xuexixuexiqq/rt-thread.git Libraries/rt-thread
