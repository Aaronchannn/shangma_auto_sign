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
- Auto Sign-in run successful on Thu Jan  9 00:40:44 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 00:41:48 UTC 2025
- Auto Sign-in run successful on Sat Jan 11 00:41:04 UTC 2025
- Auto Sign-in run successful on Sun Jan 12 00:45:08 UTC 2025
- Auto Sign-in run successful on Mon Jan 13 00:43:48 UTC 2025
- Auto Sign-in run successful on Tue Jan 14 00:38:59 UTC 2025
- Auto Sign-in run successful on Wed Jan 15 00:39:49 UTC 2025
- Auto Sign-in run successful on Thu Jan 16 00:39:35 UTC 2025
- Auto Sign-in run successful on Fri Jan 17 00:39:16 UTC 2025
- Auto Sign-in run successful on Sat Jan 18 00:37:58 UTC 2025
- Auto Sign-in run successful on Sun Jan 19 00:42:55 UTC 2025
- Auto Sign-in run successful on Mon Jan 20 00:40:53 UTC 2025
- Auto Sign-in run successful on Tue Jan 21 00:39:20 UTC 2025
- Auto Sign-in run successful on Wed Jan 22 00:40:19 UTC 2025
- Auto Sign-in run successful on Thu Jan 23 00:39:53 UTC 2025
- Auto Sign-in run successful on Fri Jan 24 00:39:44 UTC 2025
- Auto Sign-in run successful on Sat Jan 25 00:38:39 UTC 2025
- Auto Sign-in run successful on Sun Jan 26 00:40:52 UTC 2025
- Auto Sign-in run successful on Mon Jan 27 00:40:58 UTC 2025
- Auto Sign-in run successful on Tue Jan 28 00:39:54 UTC 2025
- Auto Sign-in run successful on Wed Jan 29 00:39:47 UTC 2025
- Auto Sign-in run successful on Thu Jan 30 00:38:58 UTC 2025
- Auto Sign-in run successful on Fri Jan 31 00:39:47 UTC 2025
- Auto Sign-in run successful on Sat Feb  1 00:42:41 UTC 2025
- Auto Sign-in run successful on Sun Feb  2 00:42:26 UTC 2025
- Auto Sign-in run successful on Mon Feb  3 00:41:30 UTC 2025
- Auto Sign-in run successful on Tue Feb  4 00:40:01 UTC 2025
- Auto Sign-in run successful on Wed Feb  5 00:40:18 UTC 2025
- Auto Sign-in run successful on Thu Feb  6 00:40:37 UTC 2025
- Auto Sign-in run successful on Fri Feb  7 00:40:25 UTC 2025
- Auto Sign-in run successful on Sat Feb  8 00:39:21 UTC 2025
- Auto Sign-in run successful on Sun Feb  9 00:43:10 UTC 2025
- Auto Sign-in run successful on Mon Feb 10 00:41:38 UTC 2025
- Auto Sign-in run successful on Tue Feb 11 00:40:34 UTC 2025
- Auto Sign-in run successful on Wed Feb 12 00:40:33 UTC 2025
- Auto Sign-in run successful on Thu Feb 13 00:40:47 UTC 2025
- Auto Sign-in run successful on Fri Feb 14 00:40:31 UTC 2025
- Auto Sign-in run successful on Sat Feb 15 00:39:56 UTC 2025
- Auto Sign-in run successful on Sun Feb 16 00:44:15 UTC 2025
- Auto Sign-in run successful on Mon Feb 17 00:42:55 UTC 2025
- Auto Sign-in run successful on Tue Feb 18 00:40:24 UTC 2025
- Auto Sign-in run successful on Wed Feb 19 00:40:42 UTC 2025
- Auto Sign-in run successful on Thu Feb 20 00:41:07 UTC 2025
- Auto Sign-in run successful on Fri Feb 21 00:41:22 UTC 2025
- Auto Sign-in run successful on Sat Feb 22 00:39:16 UTC 2025
- Auto Sign-in run successful on Sun Feb 23 00:44:07 UTC 2025
- Auto Sign-in run successful on Mon Feb 24 00:42:38 UTC 2025
- Auto Sign-in run successful on Tue Feb 25 00:41:41 UTC 2025
- Auto Sign-in run successful on Wed Feb 26 00:41:27 UTC 2025
- Auto Sign-in run successful on Thu Feb 27 00:41:42 UTC 2025
- Auto Sign-in run successful on Fri Feb 28 00:41:42 UTC 2025
- Auto Sign-in run successful on Sat Mar  1 00:45:15 UTC 2025
- Auto Sign-in run successful on Sun Mar  2 00:44:41 UTC 2025
- Auto Sign-in run successful on Mon Mar  3 00:43:57 UTC 2025
- Auto Sign-in run successful on Tue Mar  4 00:42:31 UTC 2025
- Auto Sign-in run successful on Wed Mar  5 00:42:38 UTC 2025
- Auto Sign-in run successful on Thu Mar  6 00:42:24 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 00:42:26 UTC 2025
- Auto Sign-in run successful on Sat Mar  8 00:33:32 UTC 2025
- Auto Sign-in run successful on Sun Mar  9 00:37:30 UTC 2025
- Auto Sign-in run successful on Mon Mar 10 00:36:23 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 00:42:41 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 00:42:10 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 00:42:54 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 00:42:05 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 00:41:50 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 00:46:26 UTC 2025
- Auto Sign-in run successful on Mon Mar 17 00:44:43 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 00:42:42 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 00:43:00 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 00:42:24 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 00:43:21 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 00:41:52 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 00:47:00 UTC 2025
- Auto Sign-in run successful on Mon Mar 24 00:44:56 UTC 2025
- Auto Sign-in run successful on Tue Mar 25 00:43:41 UTC 2025
- Auto Sign-in run successful on Wed Mar 26 00:43:06 UTC 2025
- Auto Sign-in run successful on Thu Mar 27 00:43:16 UTC 2025
- Auto Sign-in run successful on Fri Mar 28 00:43:16 UTC 2025
- Auto Sign-in run successful on Sat Mar 29 00:43:02 UTC 2025
- Auto Sign-in run successful on Sun Mar 30 00:48:29 UTC 2025
- Auto Sign-in run successful on Mon Mar 31 00:46:43 UTC 2025
- Auto Sign-in run successful on Tue Apr  1 00:51:25 UTC 2025
- Auto Sign-in run successful on Wed Apr  2 00:44:11 UTC 2025
- Auto Sign-in run successful on Thu Apr  3 00:43:29 UTC 2025
- Auto Sign-in run successful on Fri Apr  4 00:43:33 UTC 2025
- Auto Sign-in run successful on Sat Apr  5 00:42:57 UTC 2025
- Auto Sign-in run successful on Sun Apr  6 00:47:42 UTC 2025
- Auto Sign-in run successful on Mon Apr  7 00:45:41 UTC 2025
- Auto Sign-in run successful on Tue Apr  8 00:43:42 UTC 2025
- Auto Sign-in run successful on Wed Apr  9 00:43:57 UTC 2025
- Auto Sign-in run successful on Thu Apr 10 00:44:03 UTC 2025
- Auto Sign-in run successful on Fri Apr 11 00:44:22 UTC 2025
- Auto Sign-in run successful on Sat Apr 12 00:43:17 UTC 2025
- Auto Sign-in run successful on Sun Apr 13 02:11:03 UTC 2025
- Auto Sign-in run successful on Mon Apr 14 00:47:57 UTC 2025
