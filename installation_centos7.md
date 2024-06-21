# 1. Presets
### 1-1. Kernel Update
> [Linux Kernel Package Download](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)

### 1-2. Set wsl2 as default.
```
wsl --set-default-version 2
```

# 2. Installation CentOS
### 2-1. Download sources file.
> [CentOS 7.9 Download](https://github.com/mishamosher/CentOS-WSL/releases/download/7.9-2211/CentOS7.zip)
> <br/>
> Download the version you need and unzip it.

### 2-2. Run `CentOS7.exe`.
> Run the `CentOS7.exe` file with administrator privileges.

# 3. Install CentOS 7 libraries.
```
yum update
yum install -y wget
yum groupinstall "Development Tools" --setopt=group_package_types=mandatory,default,optional
```
