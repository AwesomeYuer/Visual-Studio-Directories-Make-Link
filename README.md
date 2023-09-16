# Link

## Visual Studio Directories Links

```cmd

mklink /d "C:\Program Files\Microsoft Visual Studio" "D:\VisualStudio\Program Files\Microsoft Visual Studio"

mklink /d "C:\Program Files (x86)\Microsoft Visual Studio" "D:\VisualStudio\Program Files (x86)\Microsoft Visual Studio"

mklink /d "C:\Program Files (x86)\Microsoft SDKs" "D:\VisualStudio\Program Files (x86)\Microsoft SDKs" 

mklink /d "C:\Program Files (x86)\Windows Kits" "D:\VisualStudio\Program Files (x86)\Windows Kits"

mklink /d "C:\ProgramData\Package Cache" "D:\VisualStudio\ProgramData\Package Cache"

mklink /d "C:\Program Files (x86)\Android" "D:\Android\Program Files (x86)\Android"

mklink /d "C:\Program Files\Android" "D:\Android\Program Files (x86)\Android"

```

## Windows UserSecrets
```
# link to, link from
mklink /d "C:\Users\<your user name>\AppData\Roaming\Microsoft\UserSecrets" "D:\UserSecrets"
```
## WSL UserSecrets
```
# link from, link to
ln -s /mnt/d/UserSecrets /home/<your user name>/.microsoft/usersecrets
```
