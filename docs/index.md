# The Developers Friendly Open Source Workspace

## Alpine on Windows built with Python

<div class="center-div">
    <img src="images/Alpine.png" class="small-img" width="110em">
    <img src="images/Add.svg" class="small-img" width="110em">
    <img src="images/Windows.svg" class="small-img" width="100em">
    <img src="images/Add.svg" class="small-img" width="110em">
    <img src="images/Python.svg" class="small-img" width="100em">
</div>


From a Windows terminal , run:
```powershell
curl.exe -LO $url https://github.com/kindos-forge/kindos/releases/latest/download/kindos.tar.gz
wsl.exe --import KindOS $Env:USERPROFILE\KindOS kindos.tar.gz

# Enter KindOS
wsl -d KindOS
```
