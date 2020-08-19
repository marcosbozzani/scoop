# scoop bucket

[![GitHub](https://img.shields.io/github/license/marcosbozzani/scoop)](https://github.com/marcosbozzani/scoop/blob/master/LICENSE)

- Install `scoop`. Open PowerShell 5 (or later, include PowerShell Core) and execute:
    ```powershell
    Set-ExecutionPolicy RemoteSigned -scope CurrentUser
    Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')
    ```
- Add this bucket: `scoop bucket add marcosbozzani https://github.com/marcosbozzani/scoop`
- More information: https://scoop.sh
