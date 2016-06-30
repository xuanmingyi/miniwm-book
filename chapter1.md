## Makefile
项目使用Makefile来编译,项目直接通过make命令来编译


    miniwm:miniwm.c
        gcc -o miniwm miniwm.c

## Xephyr
启动X模拟器


    Xephyr -ac -screen 1440x900 :1

检测是否启动成功


    DISPLAY=:1 xterm
