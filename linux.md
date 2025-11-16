ps -o user= -p <PID>

### 查看当前哪些 CPU 可用
cat /sys/devices/system/cpu/online

###  查看每个 CPU 的信息
cat /proc/cpuinfo

看所有 CPU，想看数量就:

grep -c ^processor /proc/cpuinfo

### 查看当前系统识别到的所有 CPU
nproc

### 查看 CPU 总数量和核心数
lscpu
