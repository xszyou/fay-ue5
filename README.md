<p align="center">
  <strong>-------> |</strong>
  <a href="/LanguageReadme/README.md">中文</a> |
  <a href="/LanguageReadme/README.ru.md">Russian</a> |
  <a href="/LanguageReadme/README.en.md">English</a> |
  <a href="/LanguageReadme/README.fr.md">Français</a>
  <strong>| <-------</strong>
</p>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-blue?style=flat&logo=github)](https://github.com/xszyou)
[![License](https://img.shields.io/badge/License-purple?style=flat&logo=github)](https://github.com/xszyou/fay-ue5/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/xszyou/fay-ue5?style=flat&logo=github&label=Stars&color=orange)](https://github.com/xszyou)

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/icon.png" alt="Fay">
    <img alt="Project Logo" src="./images/icon.png" alt="Fay" width="256" height="auto">
  </picture>
    <h1>FAY</h1>
    <h2>UE5 数字人工程(Metahuman)</h2>
</div>

---

- [此工程是一个完整的UE数字字人开源工程，可以配合Fay数字人框架，实现各种应用场景：虚拟主播、现场推销货、商品导购、语音助理、远程语音助理、数字人互动、数字人面试官及心理测评、贾维斯、Her](https://github.com/xszyou/Fay)

- 加入交流群请关注公众号：fay数字人，文档地址：[​‌metahuman(ue) - 飞书云文档](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg)

# UE 数字人启动
| | |
|-------------:|:-------------|
| **课程ID**     | `course-1775792095810` |
| **作者**       | `郭泽斌` |
| **版本**       | `1.0.` |
| **章节数**     | `5` |
| **播放及修改** | https://player.fay-agent.com |
| **导入课程包** | [UE 数字人启动.zip](<./UE 数字人启动.zip>) |



## 封面

![UE 数字人启动 封面](<./images/course1/cover.png>)

## 目录

> 1. 机器要求
> 2. 安装并启动 Fay 框架
> 3. 开麦克风及唤醒、关扬声器
> 4. 下载并运行 UE 数字人运行包
> 5. 验证连接与对话测试

---

## 第1节 机器要求

![讲义](<./images/course1/section-01-01.png>)

> [!NOTE]
> `本教程要求主机配置不低于：RTX 2050显卡、7代i7、16G内存、100G硬盘、win 10以上操作系统。`
> 
> `本教程要求主机配置不低于：RTX 2050显卡、7代i7、16G内存、100G硬盘、win 10以上操作系统。`

---

## 第2节 安装并启动 Fay 框架

![讲义](<./images/course1/section-02-01.png>)


启动 UE 数字人的第一步，是安装并启动 Fay 框架。

Fay 是本次数字人方案的核心驱动框架，负责处理语音识别、对话生成以及语音合成等关键环节。

请先按照右侧代码块中提供的官方文档网址，完成 Fay 的下载与安装。官方文档中包含了完整的环境依赖说明和安装步骤，请严格按照要求操作。

安装完成后，打开 Fay 的主界面。你会看到一个简洁的控制台页面，左侧菜单包含了消息、人设、MCP 等功能入口。

在 Fay 主页上，左下角有一个醒目的绿色圆形开机按钮。点击这个按钮，就可以一键启动 Fay 的核心服务。

启动成功后，Fay 的状态指示灯会亮起，代表系统已经进入运行状态，准备好与 UE 数字人进行对接了。

> [!NOTE]
> Fay 数字人框架官方文档
> 请按照以下网址的说明完成 Fay 的下载、安装与启动
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> 安装完成后，点击 Fay 主页左下角的绿色圆形按钮即可启动 Fay 服务。

---

## 第3节 开麦克风及唤醒、关扬声器

![讲义](<./images/course1/section-03-01.png>)


Fay 启动完成之后，接下来要做的一件非常关键的事情，就是确认麦克风处于开启状态，扬声器关闭，及唤醒开启。
今天演示的这个ue数字人模型并没有独立的拾音模块，得依赖本地机器上的fay。但有独立的声音播放模块，会播放fay合城的音频，但这音频仍须在同一台机器上。
在 Fay 的唤醒功能关闭之后，如果你没有专业的拾音硬件支持，那么 Fay 可能会把数字人自己发出的声音重新拾取进去，造成回声循环，严重影响对话体验。

配置完成后，你就可以尝试对着麦克风说一句"你好，你在吗"，验证一下 Fay 是否能够正常接收到你的声音。

---

## 第4节 下载并运行 UE 数字人运行包

![讲义](<./images/course1/section-04-01.png>)


Fay 一侧的准备工作完成之后，接下来我们需要下载并启动 UE 数字人的运行包。

请到以下网址下载最新版本的 UE 数字人运行包。下载完成后，将压缩包解压到一个独立的目录中，然后双击运行其中的 exe 可执行文件。

运行包启动之后，UE 数字人会在一个独立的窗口中呈现。你会看到一位身着白色职业装的虚拟形象站在舞台上。

数字人启动后，会自动尝试连接到本地已经运行的 Fay 服务。整个连接过程是自动完成的，你不需要手动进行任何网络配置或地址设置。这种自动连接的设计大大简化了部署流程，让非技术用户也能够快速上手，降低了搭建一套完整数字人系统的门槛。

> [!NOTE]
> UE 数字人运行包下载地址
> 
> 下载后请解压并双击运行其中的 exe 可执行文件
> 
> 数字人启动后会自动连接到本地运行中的 Fay 服务
> 
> https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd

---

## 第5节 验证连接与对话测试

![讲义](<./images/course1/section-05-01.png>)


最后一步，是验证 UE 数字人与 Fay 的连接是否成功，并进行一次完整的对话测试。

UE 数字人启动后，请回到 Fay 的管理界面进行查看。在左上角 Fay 的 Logo 位置，你会看到几个状态指示灯——如果第二个灯点亮，就代表 UE 数字人已经成功连接到了 Fay 服务，双端通信链路已经完全建立。

确认连接成功之后，你就可以对着麦克风向数字人打招呼了。尝试说一句："你好，请介绍一下你自己。"然后观察数字人的反应。

如果你看到数字人出现了口型与表情的变化，并且从 UE 数字人的运行窗口听到了清晰的语音回复，那么恭喜你，你已经成功完成了 UE 数字人的启动与对接！

到这里，整个 UE 数字人启动流程就全部完成了。你现在拥有了一个可以听、可以说、可以互动的数字人伙伴，接下来就可以开始探索更多有趣的应用场景了。

---
---

# UE 数字人工程编辑
| | |
|:-------------|:-------------|
| **课程ID**     | `course-1775804088429` |
| **作者**       | `郭泽斌` |
| **版本**       | `1.0.0` |
| **章节数**     | `11` |
| **播放及修改** | https://player.fay-agent.com |
| **导入课程包** | [UE 数字人工程编辑.zip](<./UE 数字人工程编辑.zip>) |

## 封面

![UE 数字人工程编辑 封面](<./images/course2/cover.png>)

## 目录

> 1. 机器要求
> 2. 安装并启动 Fay 框架
> 3. 开麦克风及唤醒、关扬声器
> 4. 安装epic game launcher
> 5. 安装ue 5.6 引擎
> 6. 下载并解压 UE 数字人工程包
> 7. 安装插件
> 8. 启动工程
> 9. 检查插件
> 10. 运行工程预览
> 11. 验证连接与对话测试

---

## 第1节 机器要求

![讲义](<./images/course2/section-01-01.png>)

> [!NOTE]
> `本教程要求主机配置不低于：RTX 3060显卡、10代i7、32G内存、200硬盘、win 10以上操作系统。`
> 
> `本教程要求主机配置不低于：RTX 3060显卡、10代i7、32G内存、200硬盘、win 10以上操作系统。`

---

## 第2节 安装并启动 Fay 框架

![讲义](<./images/course2/section-02-01.png>)


启动 UE 数字人的第一步，是安装并启动 Fay 框架。

Fay 是本次数字人方案的核心驱动框架，负责处理语音识别、对话生成以及语音合成等关键环节。

请先按照右侧代码块中提供的官方文档网址，完成 Fay 的下载与安装。官方文档中包含了完整的环境依赖说明和安装步骤，请严格按照要求操作。

安装完成后，打开 Fay 的主界面。你会看到一个简洁的控制台页面，左侧菜单包含了消息、人设、MCP 等功能入口。

在 Fay 主页上，左下角有一个醒目的绿色圆形开机按钮。点击这个按钮，就可以一键启动 Fay 的核心服务。

启动成功后，Fay 的状态指示灯会亮起，代表系统已经进入运行状态，准备好与 UE 数字人进行对接了。

> [!NOTE]
> Fay 数字人框架官方文档
> 
> 请按照以下网址的说明完成 Fay 的下载、安装与启动
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> 安装完成后，点击 Fay 主页左下角的绿色圆形按钮即可启动 Fay 服务。

---

## 第3节 开麦克风及唤醒、关扬声器

![讲义](<./images/course2/section-03-01.png>)


Fay 启动完成之后，接下来要做的一件非常关键的事情，就是确认麦克风处于开启状态，扬声器关闭，及唤醒开启。
今天演示的这个ue数字人模型并没有独立的拾音模块，得依赖本地机器上的fay。但有独立的声音播放模块，会播放fay合城的音频，但这音频仍须在同一台机器上。
在 Fay 的唤醒功能关闭之后，如果你没有专业的拾音硬件支持，那么 Fay 可能会把数字人自己发出的声音重新拾取进去，造成回声循环，严重影响对话体验。

配置完成后，你就可以尝试对着麦克风说一句"你好，你在吗"，验证一下 Fay 是否能够正常接收到你的声音。

---

## 第4节 安装epic game launcher

![讲义](<./images/course2/section-04-01.png>)


接下来，我们到ue官网 https://www.epicgames.com  下载 epic installer ，并完成安装。

> 
> 
> ue官网：https://www.epicgames.com
> 
> 

---

## 第5节 安装ue 5.6 引擎

![讲义](<./images/course2/section-05-01.png>)


接下来，我们打开epic game launcher,选中左侧“虚幻引擎”栏，再从顶栏选择“库”，点击引擎版本那里的加号，在下方出现的引擎方块下拉选择版本5.6，点击安装，等待安装完成。

> 
> 注：作者图示里没有5.6是因为已经安装过
> 

---

## 第6节 下载并解压 UE 数字人工程包

![讲义](<./images/course2/section-06-01.png>)


接下来我们需要下载并启动 UE 数字人的工程包。

请到以下网址下载最新版本的 UE 数字人工程包。下载完成后，将压缩包解压到一个独立的目录中备用。

> 
> https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
> 

---

## 第7节 安装插件

5.6引擎安装完成后，可到epic launcher搜索并安装图中插件。当然，你也可向fay数字人社区工作人员索取插件包。把插件解压到数字人工程的plugins目录即可。

---

## 第8节 启动工程

![讲义](<./images/course2/section-08-01.png>)


点击目录中的uproject文件，等待启动完成，此时应注意c盘留有100g以上空间，否则很可能会加载失败。

---

## 第9节 检查插件

![讲义](<./images/course2/section-09-01.png>)


工程启动后点击菜单“工具”，选择“插件”，再选择已安装，确保刚才的4个插件已经处于选中状态。

---

## 第10节 运行工程预览

![讲义](<./images/course2/section-10-01.png>)


关闭插件后，点击上方“运行”按钮，将看到数字人处于预览运行状态。数字人会自动连接上fay的。

---

## 第11节 验证连接与对话测试

![讲义](<./images/course2/section-11-01.png>)


最后一步，是验证 UE 数字人与 Fay 的连接是否真正成功，并进行一次完整的对话测试。

UE 数字人启动后，请回到 Fay 的管理界面进行查看。在左上角 Fay 的 Logo 位置，你会看到几个状态指示灯——如果第二个灯点亮，就代表 UE 数字人已经成功连接到了 Fay 服务，双端通信链路已经完全建立。

确认连接成功之后，你就可以对着麦克风向数字人打招呼了。尝试说一句："你好，请介绍一下你自己。"然后观察数字人的反应。

如果你看到数字人出现了口型与表情的变化，并且从 UE 数字人的运行窗口听到了清晰的语音回复，那么恭喜你，你已经成功完成了 UE 数字人的启动与对接！

到这里，整个 UE 数字人启动流程就全部完成了。你现在拥有了一个可以听、可以说、可以互动的数字人伙伴，接下来就可以开始探索更多有趣的应用场景了。

---
---

# UE专项交流群（插件免费获取及安静交流）
![交流群](<./images/1280X1280.JPEG>)
