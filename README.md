## Steps To Compile RTAI with the appropriate kernel

### 1- Get my RTAI
Clone this repository (the stable branch)
```bash
git clone -b stable https://github.com/adnan-saood/RTAI5.git
```

### 2- Get New Kernel sources 
Navgate to `arch/x86/patches/` folder and see the HAL patches. Choose one version and download the
matching linux kernel from `www.kernel.org`

### 3- Extract
Extract the sources of the kernel in a directory that your user owns
```bash
xzc ....
```

### 4- Get Your kernel version sources
Download the souirce code of the kernel that matches your current linux kernel (this is to copy the signature)


### 5- Admin rights
Give permission to all the users to edit and accwess the source files of the kernel and the RTAI repo
```bash
chmod a+x */*
```
