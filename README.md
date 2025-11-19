<div align="center">

# OplusKeyHook v1.1

**一款针对搭载ColorOS且配备快捷键的手机进行功能自定义的模块**

[![GitHub release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/me.siowu.OplusKeyHook?style=flat-square)](https://github.com/Xposed-Modules-Repo/me.siowu.OplusKeyHook/releases)
[![GitHub stars](https://img.shields.io/github/stars/Xposed-Modules-Repo/me.siowu.OplusKeyHook?style=flat-square&color=yellow)](https://github.com/Xposed-Modules-Repo/me.siowu.OplusKeyHook/stargazers)
<a href="https://github.com/siowu/OplusKeyHook">
        <img src="https://img.shields.io/badge/Github-OplusKeyHook-yellow.svg" alt="socialify"/>
</a>
</div>

---

本模块通过Hook原生系统按键监听逻辑，实现快捷键的事件拦截，无额外功率消耗

## ✨核心功能

- 支持一键设置成打开微信/支付宝付款码、扫一扫
- 支持打开自定义Activity [自定义Activity教程](#activity_tip) 
- 支持调用自定义Url Scheme [自定义UrlScheme教程](#url_tip) 
- 支持自定义是否震动反馈、息屏状态下是否执行，并亮屏等待解锁

## 🚀使用教程

1. 设备需安装Xposed环境并激活本模块
2. 将作用域勾选为「系统框架」
3. 重启手机，打开模块选择需要定义的功能，保存即可立即生效  
   *注：仅首次激活需要重启，后续在模块中修改按键功能无需重启*

## 🎯后续规划

当前为初步版本，后续可能加入以下功能：<br>
~~1. 区分单击、长按、双击的单独功能设置~~ (v1.1版本已实现)<br>
2. 支持执行自定义Shell命令

## 📝更新日志

v1.1 新增区分短按、双击、长按功能

## 📄 贡献

欢迎提交 [Issues](https://github.com/siowu/OplusKeyHook/issues) 与 [PRs](https://github.com/siowu/OplusKeyHook/pulls)！如果你希望适配更多应用或扩展功能，欢迎共建

使用中若有问题或建议，可通过以下方式反馈：
酷安: [@西瓜味的奥利奥](https://www.coolapk.com/u/1068187) 
Github: [@siowu](https://github.com/siowu/OplusKeyHook)

提交反馈时，请附：系统版本、设备信息、模块版本、复现步骤及日志要点，便于快速定位与修复。

## 🛡️ 免责声明

本模块仅供学习与技术研究使用，请勿用于任何违反法律法规的用途。作者不对使用本模块造成的任何后果承担责任。




<a id="activity_tip"></a>
### ✅自定义Activity教程
1. 下载 [创建快捷方式](https://www.123865.com/s/WolYjv-9yqY) APP
2. 找到想打开的软件的Activity详情页面，将图片中的两个框的内容复制到模块对应的两个输入框
 <img src="https://raw.githubusercontent.com/siowu/OplusKeyHook/refs/heads/main/images/shortcut.jpg" width="300"><br>
3. 保存即可

<a id="url_tip"></a>
### ✅自定义UrlScheme教程
1. 百度搜索常用软件UrlScheme
[常用UrlScheme大全](https://blog.csdn.net/qq_39714355/article/details/95320267)
