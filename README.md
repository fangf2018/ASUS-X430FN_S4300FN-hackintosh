# ASUS-X430FN_S4300FN-hackintosh

##配置

* 华硕灵耀S 2代 S4300FN
* CPU：i5 8265U

##驱动情况

* 显卡：核心显卡驱动正常，外接HDMI正常
* 声卡：alc256 id注入56
* 睡眠唤醒：无异常
* 键盘：快捷键无问题，禁用触摸板会偶尔无法开启
* USB：3.0最大速率5G，右侧type-c接口未驱动

##更新日志

2020-01-17

* 制声卡id为77，提交合并到applealc [查看](https://github.com/acidanthera/AppleALC/pull/650) alcid=56 开机默认为外置扬声器