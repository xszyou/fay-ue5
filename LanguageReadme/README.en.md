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
[![GitHub Stars](https://img.shields.io/github/stars/xszyou?style=flat&logo=github&label=Stars&color=orange)](https://github.com/xszyou)

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="../images/icon.png" alt="Fay">
    <img alt="Project Logo" src="../images/icon.png" alt="Fay" width="256" height="auto">
  </picture>
    <h1>FAY</h1>
    <h2>UE5 Digital Human Project (Metahuman)</h2>
</div>

---

- [This project is a complete UE digital human open-source project that can be used with the Fay digital human framework to achieve various application scenarios: virtual hosts, live product promotion, product guides, voice assistants, remote voice assistants, digital human interaction, digital human interviewers and psychological assessments, Jarvis, Her](https://github.com/xszyou/Fay)

- To join the discussion group, follow the official account: Fay Digital Human. Documentation is available at: [​‌metahuman(ue) - Feishu Cloud Document](https://qqk9ntwbcit.feishu.cn/wiki/N33FwegdxiRXzCkZlH2czjwvnrg)

# UE Digital Human Startup
| | |
|-------------:|:-------------|
| **Course ID**     | `course-1775792095810` |
| **Author**       | `Guo Zebin` |
| **Version**       | `1.0.` |
| **Number of Chapters**     | `5` |
| **Play and Modify** | https://player.fay-agent.com |
| **Import Course Package** | [UE Digital Human Startup.zip](<../UE 数字人启动.zip>) |

## Cover

![UE Digital Human Startup Cover](<../images/course1/cover.png>)

## Table of Contents

> 1. Machine Requirements  
> 2. Install and Start Fay Framework  
> 3. Enable Microphone and Wake-Up, Disable Speaker  
> 4. Download and Run UE Digital Human Runtime Package  
> 5. Verify Connection and Test Conversation  

---

## Section 1: Machine Requirements

![Lecture](<../images/course1/section-01-01.png>)

> [!NOTE]
> `This tutorial requires a host configuration of at least: RTX 2050 graphics card, 7th Gen i7, 16GB RAM, 100GB hard drive, Windows 10 or above.`  
> 
> `This tutorial requires a host configuration of at least: RTX 2050 graphics card, 7th Gen i7, 16GB RAM, 100GB hard drive, Windows 10 or above.`

---

## Section 2: Install and Start Fay Framework

![Lecture](<../images/course1/section-02-01.png>)

The first step to starting the UE digital human is to install and start the Fay framework.

Fay is the core driver framework for this digital human solution, responsible for handling key processes such as speech recognition, dialogue generation, and speech synthesis.

Please follow the official documentation website provided in the code block on the right to complete the download and installation of Fay. The official documentation includes a complete description of environment dependencies and installation steps. Please strictly follow the instructions.

After installation, open the Fay main interface. You will see a simple console page, with the left menu containing entry points for functions such as messages, personas, and MCP.

On the Fay homepage, there is a prominent green circular power button at the bottom left. Click this button to start the core services of Fay with one click.

Once started successfully, the status indicator light on Fay will turn on, indicating that the system is now running and ready to interface with the UE digital human.

> [!NOTE]
> Fay Digital Human Framework Official Documentation  
> Please follow the instructions at the following URL to complete the download, installation, and startup of Fay:  
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc  
> 
> After installation, click the green circular button at the bottom left of the Fay homepage to start the Fay service.

---

## Section 3: Enable Microphone and Wake-Up, Disable Speaker

![Lecture](<../images/course1/section-03-01.png>)

After Fay has started successfully, the next critical step is to ensure that the microphone is enabled, the speaker is disabled, and wake-up is enabled.  

The UE digital human model demonstrated today does not have an independent sound pickup module and relies on Fay running on the local machine. However, it does have an independent sound playback module that plays audio synthesized by Fay. This audio must still be played on the same machine.  

If Fay's wake-up function is disabled and you lack professional sound pickup hardware, Fay may pick up the sound emitted by the digital human itself, causing echo loops that severely affect the conversation experience.

Once the configuration is complete, you can try speaking into the microphone and say, "Hello, are you there?" to verify whether Fay can receive your voice correctly.

---

## Section 4: Download and Run UE Digital Human Runtime Package

![Lecture](<../images/course1/section-04-01.png>)

After completing the preparation on Fay's side, the next step is to download and start the UE digital human runtime package.

Please download the latest version of the UE digital human runtime package from the following URL. Once downloaded, extract the compressed file into a separate directory and double-click the executable file within to run it.

Once the runtime package starts, the UE digital human will appear in a separate window. You will see a virtual figure dressed in white professional attire standing on a stage.

After the digital human starts, it will automatically attempt to connect to the locally running Fay service. The entire connection process is completed automatically, and you do not need to manually configure any network settings or addresses. This automatic connection design greatly simplifies the deployment process, enabling non-technical users to quickly get started and lowering the barrier to setting up a complete digital human system.

> [!NOTE]
> UE Digital Human Runtime Package Download Address  
> 
> After downloading, extract the files and double-click the executable file to run.  
> 
> Once started, the digital human will automatically connect to the locally running Fay service.  
> 
> https://pan.baidu.com/s/1olc-Jd9rH-PcWkdBK2Hc6Q?pwd=kwyd

---

## Section 5: Verify Connection and Test Conversation

![Lecture](<../images/course1/section-05-01.png>)

The final step is to verify whether the connection between the UE digital human and Fay was successful and conduct a complete conversation test.

After the UE digital human starts, return to the Fay management interface to check. At the top left of Fay's logo position, you will see several status indicator lights—if the second light is on, it means the UE digital human has successfully connected to the Fay service, and the communication link between the two ends has been fully established.

Once the connection is confirmed, you can speak into the microphone and greet the digital human. Try saying, "Hello, please introduce yourself," and observe the digital human's response.

If you see the digital human's mouth and facial expressions change and hear a clear voice response from the UE digital human's runtime window, congratulations! You have successfully completed the startup and integration of the UE digital human.

At this point, the entire UE digital human startup process is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more interesting application scenarios.

---
---

# UE Digital Human Project Editing
| | |
|:-------------|:-------------|
| **Course ID**     | `course-1775804088429` |
| **Author**       | `Guo Zebin` |
| **Version**       | `1.0.0` |
| **Number of Chapters**     | `11` |
| **Play and Modify** | https://player.fay-agent.com |
| **Import Course Package** | [UE Digital Human Project Editing.zip](<../UE 数字人工程编辑.zip>) |

## Cover

![UE Digital Human Project Editing Cover](<../images/course2/cover.png>)

## Table of Contents

> 1. Machine Requirements  
> 2. Install and Start Fay Framework  
> 3. Enable Microphone and Wake-Up, Disable Speaker  
> 4. Install Epic Games Launcher  
> 5. Install UE 5.6 Engine  
> 6. Download and Extract UE Digital Human Project Package  
> 7. Install Plugins  
> 8. Start Project  
> 9. Check Plugins  
> 10. Run Project Preview  
> 11. Verify Connection and Test Conversation  

---

## Section 1: Machine Requirements

![Lecture](<../images/course2/section-01-01.png>)

> [!NOTE]
> `This tutorial requires a host configuration of at least: RTX 3060 GPU, 10th Gen i7, 32GB RAM, 200GB storage, and Windows 10 or higher.`
> 
> `This tutorial requires a host configuration of at least: RTX 3060 GPU, 10th Gen i7, 32GB RAM, 200GB storage, and Windows 10 or higher.`

---

## Section 2: Installing and Launching the Fay Framework

![Lecture](<../images/course2/section-02-01.png>)

The first step to launching the UE Metahuman is to install and launch the Fay framework.

Fay is the core driving framework for this Metahuman solution, responsible for handling key processes such as speech recognition, dialogue generation, and speech synthesis.

Please follow the official documentation URL provided in the code block on the right to complete the download and installation of Fay. The official documentation includes a complete description of the environment dependencies and installation steps, so be sure to follow the instructions carefully.

After installation, open the main interface of Fay. You will see a simple console page, with the left menu containing functional entries such as Messages, Personas, and MCP.

On the Fay homepage, there is a prominent green circular power button in the bottom left corner. Click this button to start Fay's core services with one click.

Once successfully launched, Fay's status indicator light will turn on, indicating that the system is now running and ready to interface with the UE Metahuman.

> [!NOTE]
> Fay Metahuman Framework Official Documentation
> 
> Please follow the instructions at the following URL to download, install, and launch Fay:
> 
> https://qqk9ntwbcit.feishu.cn/wiki/V5qcwlikKiehoYkAPhYcmBPAnAc
> 
> After installation, click the green circular button in the bottom left corner of the Fay homepage to start the Fay service.

---

## Section 3: Enabling the Microphone and Wake-Up, Disabling the Speaker

![Lecture](<../images/course2/section-03-01.png>)

After Fay is launched, the next critical step is to ensure that the microphone is enabled, the speaker is disabled, and the wake-up function is turned on.

The UE Metahuman model demonstrated today does not have an independent audio capture module and relies on Fay on the local machine. However, it does have an independent audio playback module that plays the audio synthesized by Fay, but this audio must still be on the same machine.

If Fay's wake-up function is disabled and you do not have professional audio capture hardware, Fay might pick up the sound emitted by the Metahuman itself, causing an echo loop that severely affects the conversation experience.

Once the configuration is complete, you can try speaking into the microphone and say, "Hello, are you there?" to verify if Fay can receive your voice correctly.

---

## Section 4: Installing the Epic Games Launcher

![Lecture](<../images/course2/section-04-01.png>)

Next, go to the UE official website https://www.epicgames.com to download the Epic Games Launcher and complete the installation.

> 
> 
> UE official website: https://www.epicgames.com
> 
> 

---

## Section 5: Installing the UE 5.6 Engine

![Lecture](<../images/course2/section-05-01.png>)

Next, open the Epic Games Launcher, select the "Unreal Engine" tab on the left, then choose "Library" from the top menu. Click the plus sign next to the engine version, select version 5.6 from the dropdown in the engine block that appears below, and click install. Wait for the installation to complete.

> 
> Note: The 5.6 version is not shown in the author's illustration because it has already been installed.
> 

---

## Section 6: Downloading and Extracting the UE Metahuman Project Package

![Lecture](<../images/course2/section-06-01.png>)

Next, we need to download and launch the UE Metahuman project package.

Please download the latest version of the UE Metahuman project package from the following URL. After downloading, extract the compressed file to a separate directory for later use.

> 
> https://pan.baidu.com/s/1aApeAiIwGNvPXxR-gBj_MQ?pwd=q2jw
> 

---

## Section 7: Installing Plugins

After installing the 5.6 engine, you can search for and install the plugins shown in the image through the Epic Games Launcher. Alternatively, you can request the plugin package from the Fay Metahuman community staff. Extract the plugins into the Plugins directory of the Metahuman project.

---

## Section 8: Launching the Project

![Lecture](<../images/course2/section-08-01.png>)

Click the uproject file in the directory and wait for the launch to complete. Make sure there is at least 100GB of free space on the C drive; otherwise, the loading may fail.

---

## Section 9: Checking Plugins

![Lecture](<../images/course2/section-09-01.png>)

After the project launches, click the "Tools" menu, select "Plugins," and then choose "Installed." Ensure that the four plugins installed earlier are enabled.

---

## Section 10: Running the Project Preview

![Lecture](<../images/course2/section-10-01.png>)

After closing the plugin menu, click the "Play" button at the top. You will see the Metahuman running in preview mode. The Metahuman will automatically connect to Fay.

---

## Section 11: Verifying Connection and Testing Dialogue

![Lecture](<../images/course2/section-11-01.png>)

The final step is to verify whether the UE Metahuman has successfully connected to Fay and to conduct a complete dialogue test.

After launching the UE Metahuman, return to the Fay management interface to check. In the top-left corner where the Fay logo is displayed, you will see several status indicator lights. If the second light is on, it means the UE Metahuman has successfully connected to the Fay service, and the two-way communication link has been fully established.

Once the connection is confirmed, you can greet the Metahuman through the microphone. Try saying, "Hello, can you introduce yourself?" and observe the Metahuman's response.

If you see the Metahuman's mouth and facial expressions change and hear a clear voice response from the UE Metahuman's running window, congratulations! You have successfully completed the setup and integration of the UE Metahuman.

At this point, the entire process of setting up the UE Metahuman is complete. You now have a digital human companion that can listen, speak, and interact. You can start exploring more interesting application scenarios.

---
---

# UE Special Interest Group (Free Plugin Access and Quiet Discussions)
![Group Chat](<../images/1280X1280.JPEG>)