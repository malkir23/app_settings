oh-my-posh init pwsh --config "D:\Develop\app_settings\oh-my-posh\my-theme.omp.json" | Invoke-Expression
Install-Module PSReadLine -Force

Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView