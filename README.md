#### 获取root权限
```
adb -d shell
```
多个设备则先获取设备id
```
adb devices
```
再通过 ``` adb -s ID shell ``` 获取。
再命令行中输入 ``` su ``` 进入root权限，当命令行前是 # 则代表获取了最高管理员权限
