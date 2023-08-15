usage:
1. clone项目https://github.com/matrix1001/glibc-all-in-one ，并按照说明初始化。
2. 添加全局变量GAIO_PATH为glibc-all-in-one所在的目录,例如"/home/ubuntu/Tools/glibc-all-in-one"
3. 将autopatch文件复制到/usr/local/bin并添加执行权限
4. 当某个elf文件和某个libc文件（文件名以libc开头）在同一个文件夹时，使用autopatch <elf>即可
