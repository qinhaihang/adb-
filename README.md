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

#### 删除文件
```
tools>adb remount 
tools>adb shell 
#su 
#cd system/sd/data //进入系统内指定文件夹 
#ls //列表显示当前文件夹内容 
#rm -r xxx //删除名字为xxx的文件夹及其里面的所有文件 
#rm xxx //删除文件xxx 
#rmdir xxx //删除xxx的文件夹

```
