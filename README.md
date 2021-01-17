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
* 触摸板：i2c轮询

##更新日志
2020-01-18

* 定制声卡id为88，提交合并到applealc [查看](https://github.com/acidanthera/AppleALC/pull/650) 
  该id为内置麦克风与外置麦克风分离，无需安装ComboJack 麦克风切换需要到系统便好设置进行手动切换
  
  ![](github.fangf.cc/mweb/16108895944286.jpg)

2020-01-17

* 定制声卡id为77，提交合并到applealc [查看](https://github.com/acidanthera/AppleALC/pull/650) 
  此id为内置麦克风外置麦克风合并，切换需要依靠ComboJack，插入耳麦会自动弹窗进行选择
  ⚠️从win10热重启到mac默认为外置麦克风，需要关机开机才会默认切换为内置麦克风