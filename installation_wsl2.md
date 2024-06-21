# 1. Check the support conditions.
Press the `Ctrl + Shift + Esc` keys simultaneously.  
> You should see Virtualization as shown in the below screenshot. If it is enabled, it means that your CPU supports Virtualization and is currently enabled in BIOS. If it shows disabled, you need to enable it in BIOS. If you don’t see virtualization, it means that your CPU does not support virtualization.  
  
![Screenshot 2024-06-21 113741](https://github.com/wantedweb-kevin/wsl2/assets/79559317/9820112c-1ba6-4d61-8920-603976c1049b)

<br/>
<br/>
<br/>

# 2. Setting Up Windows Subsystem for Linux.
### 2-1. Enable Developer Mode.
#### 2-1-1. Search for `settings` in the start menu.
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/262f9f44-e7aa-4605-9f00-ee57d615de0b)
#### 2-1-2. Turn on `developer mode`.
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/622a1768-1820-489e-8b52-282e563d83a1)
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/a054edcb-4625-4aae-8b5e-2cd54a5ec0ed)

<br/>

### 2-2. Enable Windows Subsystem for Linux.
#### 2-2-1. Press the `Windows + R` keys simultaneously.  
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/bfbe9439-0e9a-42de-94d4-3751876fddf3)
#### 2-2-2. Run command `appwiz.cpl` to open the Programs and Features.  
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/def2b135-7b17-4d27-bc3d-8ae54528b75f)
#### 2-2-3. Activate `Hyper-V` and `Windows Subsystem for Linux`.
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/8a655821-03e8-43cc-b8a0-3d7ec451234b)
> It says the system needs to reboot for a configuration change to take effect.

<br/>
<br/>
<br/>

# 3. Install Ubuntu Linux.
#### 3-1. Open the Start menu, type `Windows PowerShell`, select Windows PowerShell, and then select Run as administrator.
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/8be8d5be-7e52-4cda-8894-4aa9ea81e257)
#### 3-2. List available Linux distributions.
```
wsl --list --online
```
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/0dd3eafb-0442-4c1d-b786-fc2e6390140b)
#### 3-3. Install the latest version of Ubuntu.
```
wsl --install -d Ubuntu
```
> To install a specific version, enter the version name as well.
> ```
> wsl --install -d Ubuntu-[version]
> ```
Reboot once installation is complete.
#### 3-4. Check installation.
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/7bd62409-3cff-461a-b878-75c6b1be6ad7)
```
explorer.exe .
```
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/b1a81aaa-e02e-4120-ab26-d301111740e7)
![image](https://github.com/wantedweb-kevin/wsl2/assets/79559317/481e9ba2-593c-4303-99b0-2a78b5b22a86)
