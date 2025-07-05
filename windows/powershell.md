# Powershell

1. 以下を参考にOh-My-Poshをインストールする  
https://qiita.com/SAITO_Keita/items/14cd9d7349bc2256b4da  

1. 設定ファイルに`oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/rudolfs-light.omp.json" | Invoke-Expression`を設定する

1. このままカラースキームをSolarized lightに設定するとスペースを入力したときにバグるので，以下を参考にPSReadLineを更新する  
https://github.com/microsoft/terminal/issues/7494
