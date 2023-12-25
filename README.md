# PoshTheme_popu
#### 这是啥？
一款基于oh my posh自用主题
#### 怎么用？
0.微软商店搜索oh my posh安装或自行前往[ohmyposh.dev](https://ohmyposh.dev/docs/installation/windows)安装  

__推荐配置方法__  
建议clone yaml到本地，启动powershell
```
curl -o $env:POSH_THEMES_PATH\popu.omp.yaml https://raw.githubusercontent.com/popu-web/PoshTheme_popu/main/popu.omp.yaml
```
powershell配置文件追加启动on my posh主题
```
Add-Content $profile "`noh-my-posh init pwsh --config `$env:POSH_THEMES_PATH\popu.omp.yaml | Invoke-Expression"
```

__在线配置，较慢__  
启动powershell
```
notepad $profile
```
记事本追加行:
```
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/popu-web/PoshTheme_popu/main/popu.omp.yaml' | Invoke-Expression
```

- - -

##### 实际效果
配色方案来自 [colordrop](https://colordrop.io/)
![Alt text](screenshot\image.png)