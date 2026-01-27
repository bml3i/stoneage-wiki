---
title: 安装与运行
hide_table_of_contents: true
sidebar_label: '安装与运行'
sidebar_position: 1
---

### 一、Windows 10/11 安全中心 添加排除项
1. 搜索并进入Windows安全中心
2. 点击左侧的"病毒和威胁防护"
3. 点击设置里的"管理设置"
4. 点击"添加或删除排除项"
5. 建议选择、添加石器游戏和外挂共同的父文件夹，例如：C:\SA2.5

<img src={require('./assets/img/security-center-exclude.png').default} alt="Windows安全中心" style={{width: 600}} />

:::tip[关于安全性]
添加排除项后，游戏和外挂将不再被Windows安全中心扫描，从而不会被误识别为病毒然后被删除。
:::



### 二、设置兼容模式和颜色模式
1. 右键点击STW外挂程序图标，选择"属性"
2. 在"兼容性"选项卡中，勾选"以兼容模式运行此程序"
3. 从下拉列表中选择"Windows XP (SP 3)"
4. 在设置中勾选"简化的颜色模式"，选择"8位(256)色"
5. 点击"应用"和"确定"

<img src={require('./assets/img/stw_8bit.png').default} alt="STW兼容性设置" style={{width: 600}} />

若未做以上设置，游戏画面会出现颜色异常，导致游戏无法正常运行。

<img src={require('./assets/img/strange_sa25_screen.jpg').default} alt="颜色异常" style={{width: 600}} />