## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Wed Dec 25 01:52:06 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 00:40:08 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 00:40:21 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 00:39:34 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 00:44:41 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 00:42:20 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 00:40:21 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 00:44:53 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 00:40:08 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 00:40:43 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 00:39:46 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 00:44:33 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 00:43:01 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 00:41:10 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 00:40:54 UTC 2025
