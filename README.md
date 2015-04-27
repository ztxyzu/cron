C# cron4win
---------------------------
支持绝大部分Windows，注意早期操作系统可能需要安装.Net Framework 3.5版本

```
*    *    *    *    *  
┬    ┬    ┬    ┬    ┬
│    │    │    │    │
│    │    │    │    │
│    │    │    │    └───── day of week (0 - 6) (Sunday=0 )
│    │    │    └────────── month (1 - 12)
│    │    └─────────────── day of month (1 - 31)
│    └──────────────────── hour (0 - 23)
└───────────────────────── min (0 - 59)
```

```
Console Example
===============
* * * * *  d:\1.exe //每分钟执行d:\1.exe程序
01 * * * * d:\1.exe //每小时执行d:\1.exe程序
02 4 * * * d:\1.exe //每天执行d:\1.exe程序
22 4 * * 0 d:\1.exe //每星期执行d:\1.exe程序
42 4 1 * * d:\1.exe //每月去执行d:\1.exe程序

```

