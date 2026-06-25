# ESystem

<div>
<span style="margin-top: -8px; display: inline-block; font-size: 13px; font-style: italic;">
下载地址：
<a href="https://gitee.com/DisciplinedFries/embedded-system/releases/tag/v1.0.0.1"
   target="_blank"
   style="font-weight: normal; text-decoration: none; font-style: italic;">
  最新版ESystem
</a>
</span>
</div>

<div>
<span style="margin-top: 4px; display: inline-block; font-size: 13px; font-style: italic;">
BiliBili地址：
<a href="https://www.bilibili.com/video/BV1kEjn6BESh/?spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=46c754a2377593e24f7b071341cfcc8b"
   target="_blank"
   style="font-weight: normal; text-decoration: none; font-style: italic;">
  B站视频介绍
</a>
</span>
</div>

## 设计初衷

-  **大家好，我是 ESystem 的开发者。** 
-  _在嵌入式开发的这些年里，我经常会面对各种各样的调试需求。有时候，我想更清晰地看到每一帧数据的收发时间；有时候，需要把重要的通信数据完整保存下来；有时候，又希望能快速解析出数据帧中特定字节或字段的实际含义…… 或者需要用图表直观地观察数据变化趋势时，又或者项目从串口切换到 TCP/UDP 网络通信时，就不得不再次寻找和切换不同的工具。于是，我常常在电脑上同时打开好几个助手软件，每个软件的操作方式都不一样，来回切换不仅麻烦，也很容易出错。_ 
-  _我越来越想要一款工具，能把这些常用功能真正集中在一起：既能像传统串口助手一样简单易用，又支持数据解析、自动保存、灵活布局，还能轻松应对图表和 TCP/UDP 网络通信的需求。即使是刚接触嵌入式开发的朋友，也能快速上手。_ 
- **ESystem 就是基于这个实际需求诞生的。** 
-  _它并不是一个把所有功能简单堆砌起来的“万能工具”，而是我在日常开发中，把自己最常用、最迫切需要的那些功能慢慢整合、反复打磨后的成果。希望 ESystem 能成为你开发路上的得力助手。_ 


## 页面介绍

### 1. 主页
<div style="font-size: 12px; line-height: 1.6;">

- [默认主题] - 界面默认采用浅色UI；若切换其他主题，重启后会自动应用您修改后的主题。
- [切换主题] - 点击左侧导航栏的“主题切换”按钮，即可更改界面配色。
- [动态演示] - 点击页面左上角的机器人图标，可展开或收起左侧导航栏。
</div>

<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>默认主题</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/1.Home/1.Home.png" width="500" style="max-height:320px; object-fit: contain;" alt="默认主题"/>
    </td>
    <td align="center">
      <strong>切换主题</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/1.Home/2.Home.png" width="500" style="max-height:320px; object-fit: contain;" alt="切换主题"/>
    </td>
    <td align="center">
      <strong>动态演示</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/1.Home/3.Home.gif" width="500" style="max-height:320px; object-fit: contain;" alt="动态切换主题"/>
    </td>
  </tr>
</table>
</div>



### 2.串口监视器
</span>

<div style="font-size: 12px; line-height: 1.6;">

- [串口配置] - 默认采用预设串口配置；若修改，重启后自动应用上次修改后的配置。
- [发送列表] - 记录发送内容、注释及自动发送等信息，配置自动保存。
- [协议解析] - 通过设置数据下标、字节数量及高\低位在前后转换成对应的数值。
- [其他配置] - 支持将接收到的数据保存为.txt文件，调整接收区最大显示长度;发送格式可通过发送配置选择Hex\文本\ASCII码。
- [帮助文档] - 提供各控件及功能的简要用法说明。
- [补充说明] - 拖动接收区与发送区之间的分隔条，可调整两者显示比例；点击🔻图标可收起或展开发送区。
</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>串口配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/2.SerialMonitor/1.SerialMonitor.png" width="500" style="max-height:320px; object-fit: contain;" alt="串口监视器"/>
    </td>
    <td align="center">
      <strong>发送列表</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/2.SerialMonitor/2.SerialMonitor.png" width="500" style="max-height:320px; object-fit: contain;" alt="发送列表"/>
    </td>
    </td>
    <td align="center">
      <strong>协议解析</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/2.SerialMonitor/3.SerialMonitor.png" width="500" style="max-height:320px; object-fit: contain;" alt="协议解析"/>
    </td>
    </td>
    <td align="center">
      <strong>其他配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/2.SerialMonitor/4.SerialMonitor.png" width="500" style="max-height:320px; object-fit: contain;" alt="其他配置"/>
    </td>
    </td>
    <td align="center">
      <strong>帮助文档</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/2.SerialMonitor/5.SerialMonitor.png" width="500" style="max-height:320px; object-fit: contain;" alt="帮助"/>
    </td>
  </tr>
</table>
</div>
 


### 3.数据可视化

<div style="font-size: 12px; line-height: 1.6;">

- [串口配置] - 默认采用预设串口配置；若修改，重启后自动应用上次修改后的配置。
- [曲线绑定] - 提供8个通道，可同时绑定并绘制8条曲线。
- [其他配置] - 待做。
- [帮助文档] - 提供各控件及功能的简要用法说明。
</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>串口配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/3.DataBoard/1.DataBoard.png" width="500" style="max-height:320px; object-fit: contain;" alt="串口配置"/>
    </td>
    <td align="center">
      <strong>曲线绑定</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/3.DataBoard/2.DataBoard.png" width="500" style="max-height:320px; object-fit: contain;" alt="曲线绑定"/>
    </td>
    </td>
    <td align="center">
      <strong>其他配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/3.DataBoard/3.DataBoard.png" width="500" style="max-height:320px; object-fit: contain;" alt="其他配置"/>
    </td>
    </td>
    <td align="center">
      <strong>帮助文档</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/3.DataBoard/4.DataBoard.png" width="500" style="max-height:320px; object-fit: contain;" alt="帮助"/>
    </td>
  </tr>
</table>
</div>
 

### 4.网络调试


<div style="font-size: 12px; line-height: 1.6;">

- [网络配置] - 默认采用预设网络配置；若修改，重启后自动应用上次修改后的配置。
- [发送列表] - 记录发送内容、注释及自动发送等信息，配置自动保存。
- [协议解析] - 通过设置数据下标、字节数量及高\低位在前后转换成对应的数值。
- [其他配置] - 支持将接收到的数据保存为.txt文件，调整接收区最大显示长度;发送格式可通过发送配置选择Hex\文本\ASCII码。
- [帮助文档] - 提供各控件及功能的简要用法说明。
</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>网络配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/4.Net/1.Net.png" width="500" style="max-height:320px; object-fit: contain;" alt="网络配置"/>
    </td>
    <td align="center">
      <strong>发送列表</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/4.Net/2.Net.png" width="500" style="max-height:320px; object-fit: contain;" alt="发送列表"/>
    </td>
    </td>
    <td align="center">
      <strong>协议解析</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/4.Net/3.Net.png" width="500" style="max-height:320px; object-fit: contain;" alt="协议解析"/>
    </td>
    </td>
    <td align="center">
      <strong>其他配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/4.Net/4.Net.png" width="500" style="max-height:320px; object-fit: contain;" alt="其他配置"/>
    </td>
    </td>
    <td align="center">
      <strong>帮助文档</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/4.Net/5.Net.png" width="500" style="max-height:320px; object-fit: contain;" alt="帮助"/>
    </td>
  </tr>
</table>
</div>


### 5.工具箱

<div style="font-size: 12px; line-height: 1.6;">

- [工具箱箱] - 默认采用预设网络配置；若修改，重启后自动应用上次修改后的配置。
- [工具介绍] - - .-- .... . -.   ..- ... .. -. --.   .. -     ... .. -- .--. .-.. -.--   . -. - . .-.   .-   ...- .- .-.. ..- .   .. -.   .- -. -.--   .. -. .--. ..- -   -... --- -..-     .- -. -..   - .... .   -.-. --- .-. .-. . ... .--. --- -. -.. .. -. --.   -... --- -..- . ...   .-- .. .-.. .-..   .- ..- - --- -- .- - .. -.-. .- .-.. .-.. -.--   -.. .. ... .--. .-.. .- -.--   - .... .   -.-. --- -. ...- . .-. ... .. --- -.   .-. . ... ..- .-.. -     -- .- -.- .. -. --.   .. -   . .- ... -.--   - ---   --.- ..- .. -.-. -.- .-.. -.--   -.-. --- -- .--. .- .-. .   .- -. -..   ...- . .-. .. ..-. -.--
- [补充说明] - 工具箱扩展：后续将根据开发计划持续增加新工具；需求反馈：若您有需要的工具，可在软件内点击提交issue提出。

</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>工具箱</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/5.Tool/1.Tool.png" width="300" style="max-height:192px; object-fit: contain;" alt="工具箱"/>
    </td>
    <td align="center">
      <strong>工具介绍</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/5.Tool/2.Tool.png" width="300" style="max-height:192px; object-fit: contain;" alt="工具介绍"/>
    </td>
  </tr>
</table>
</div>


### 6.操作与文件系统

<div style="font-size: 12px; line-height: 1.6;">

- [操作与文件系统] - 后续开发
</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>操作与文件系统</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/6.OS/1.OS.png" width="300" style="max-height:192px; object-fit: contain;" alt="操作与文件系统"/>
    </td>
    <td align="center">
      <strong>操作与文件系统视图</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/6.OS/2.OS.png" width="300" style="max-height:192px; object-fit: contain;" alt="操作与文件系统视图"/>
    </td>
  </tr>
</table>
</div>


### 7.实时通信系统

<div style="font-size: 12px; line-height: 1.6;">

- [实时通信系统] - 后续开发
</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>操作与文件系统</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/7.RealTime/1.RealTime.png" width="300" style="max-height:192px; object-fit: contain;" alt="操作与文件系统"/>
    </td>
    <td align="center">
      <strong>操作与文件系统视图</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/7.RealTime/2.RealTime.png" width="300" style="max-height:192px; object-fit: contain;" alt="操作与文件系统视图"/>
    </td>
  </tr>
</table>
</div>


### 8.系统日志

<div style="font-size: 12px; line-height: 1.6;">

- [系统配置] - 显示当前软件版本及更新状态，并提供开机自启设置选项。
- [关于软件] - 一些碎碎念。
- [补充说明] - 自动升级的具体操作步骤，请参阅文档末尾的示例。
</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>系统日志</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/8.SystemLog/1.SystemLog.png" width="500" style="max-height:320px; object-fit: contain;" alt="系统日志"/>
    </td>
    <td align="center">
      <strong>系统配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/8.SystemLog/2.SystemLog.png" width="500" style="max-height:320px; object-fit: contain;" alt="系统配置"/>
    </td>
    <td align="center">
      <strong>关于软件</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/8.SystemLog/3.SystemLog.png" width="500" style="max-height:320px; object-fit: contain;" alt="关于ESystem"/>
    </td>
  </tr>
</table>
</div>

## 操作示例
- 展示多种实际使用场景，通过调整界面布局和主题，呈现更好的视觉效果。
### 示例A
- [调整布局] - 通过调整窗口及面板布局，让数据显示更加清晰直观。
- [自动升级] - 点击更新后，软件将自动下载安装新版本并重启。
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>调整布局1</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/SerialMonitor_Examples (1).png" width="300" style="max-height:192px; object-fit: contain;" alt="串口正常通信"/>
    </td>
    <td align="center">
      <strong>调整布局2</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/SerialMonitor_Examples (2).png" width="300" style="max-height:192px; object-fit: contain;" alt="调整布局后"/>
    </td>
    <td align="center">
      <strong>自动升级1</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/SystemLog_Examples (1).png" width="500" style="max-height:320px; object-fit: contain;" alt="发现新版本"/>
    </td>
    <td align="center">
      <strong>自动升级2</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/SystemLog_Examples (2).png" width="500" style="max-height:320px; object-fit: contain;" alt="点击自动升级"/>
    </td>
  </tr>
</table>
</div>


### 示例B
- [图表示例] - 这里进行了操作演示以及调整布局，数据绑定显示简单。
- [图表配置] - 按帧接收字节数据（未做校验），下图为示例，每10ms绘制一个数据点，每帧数据长度为8字节。

<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>图表示例1</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/DataBoard_Examples (1).png" width="500" style="max-height:320px; object-fit: contain;" alt="串口正常通信"/>
    </td>
    <td align="center">
      <strong>图表示例2</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/DataBoard_Examples (2).png" width="500" style="max-height:320px; object-fit: contain;" alt="调整布局后"/>
    </td>
    <td align="center">
      <strong>图表示例3</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/DataBoard_Examples (3).png" width="500" style="max-height:320px; object-fit: contain;" alt="发现新版本"/>
    </td>
    <td align="center">
      <strong>图表示例4</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/DataBoard_Examples (4).png" width="500" style="max-height:320px; object-fit: contain;" alt="点击自动升级"/>
    </td>
    <td align="center">
      <strong>图表示例5</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/DataBoard_Examples (5).png" width="500" style="max-height:320px; object-fit: contain;" alt="点击自动升级"/>
    </td>
  </tr>
</table>
</div>


### 示例C
- [TCP服务器] - 通信示例。
- [TCP客户端] - 通信示例。

<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>TCP示例1</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/Net_Examples (1).png" width="500" style="max-height:320px; object-fit: contain;" alt="TCP示例1"/>
    </td>
    <td align="center">
      <strong>TCP示例2</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/Net_Examples (2).png" width="500" style="max-height:320px; object-fit: contain;" alt="TCP示例2"/>
    </td>
    <td align="center">
      <strong>TCP示例3</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/Net_Examples (3).png" width="500" style="max-height:320px; object-fit: contain;" alt="TCP示例3"/>
    </td>
    <td align="center">
      <strong>TCP示例4</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/Net_Examples (4).png" width="500" style="max-height:320px; object-fit: contain;" alt="TCP示例4"/>
    </td>
    <td align="center">
      <strong>TCP示例5</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/Packs/9.Examples/Net_Examples (5).png" width="500" style="max-height:320px; object-fit: contain;" alt="TCP示例5"/>
    </td>
  </tr>
</table>
</div>

## 软件基于 .NET 8 开发
<div style="font-size: 12px; line-height: 1.6;">

- 本软件依赖 .NET 8 运行环境，首次使用或系统未安装时需要进行此操作。
- 如果出现以下安装提示界面，请点击 **“Download it now”** 安装 .NET 8 桌面运行时组件。
- 最新版 ESystem.exe 和 windows 下的.NET8.0 组件已放置到仓库中的 ESystem 文件夹下，有需要自行下载。
</div>
<div align="center">
<table border="0" cellpadding="10" cellspacing="0">
  <tr>
    <td align="center">
      <strong>系统日志</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/ESystem/P1.png" width="500" style="max-height:320px; object-fit: contain;" alt="系统日志"/>
    </td>
    <td align="center">
      <strong>系统配置</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/ESystem/P2.png" width="500" style="max-height:320px; object-fit: contain;" alt="系统配置"/>
    </td>
    <td align="center">
      <strong>关于软件</strong><br>
      <img src="https://gitee.com/DisciplinedFries/embedded-system/raw/master/ESystem/P3.png" width="500" style="max-height:320px; object-fit: contain;" alt="关于ESystem"/>
    </td>
  </tr>
</table>
</div>

## 关于杀软报毒的说明
如果有杀毒软件报毒或提示有可疑行为，请先确认软件是从本页面提供的渠道下载的。
如果确认是从本页面提供的渠道下载的，那么大概率为误报。