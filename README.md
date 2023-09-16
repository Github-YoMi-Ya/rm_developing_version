# rm_developing_version

rm_version开发版本

## 这是老版本

## 食用方法

### 启动全部节点launch文件

无硬件：ros2 launch rm_vision_bringup no_hardware.launch.py

有硬件：ros2 launch rm_vision_bringup vision_bringup.launch.py

### 开启串口
sudo chmod 777 /dev/ttyUSB0

### 启动可视化：
ros2 launch foxglove_bridge foxglove_bridge_launch.xml port:=8765

### 浏览器打开可视化  
https://studio.foxglove.dev/

### 查看相机帧率
ros2 topic hz /camera_info

### 关闭所有节点
ros2 node killall

## 这是开发端口
开发流程
请参考：https://www.jianshu.com/p/9801b98c1de4

## 请使用git fork上传代码或者找我绑定项目公钥


