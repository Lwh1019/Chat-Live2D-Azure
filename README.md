# Chat-Live2D-Azure

本项目是利用OpenAI API、Mircosoft Azure、APISpace 与Live2D技术，完成的猫咪对话交流机器人。
如有错误，请求指正！

在脚本中请自行更改API为自己的API

  
# 主界面展示

黑猫和白猫

![image](https://github.com/user-attachments/assets/741eb9c9-3564-41b0-b4ce-880097b45b9a)

![image](https://github.com/user-attachments/assets/97b57497-05c1-4753-a8c8-ad4085785e3c)

同时利用Live2D的SDK，使得小猫视角能够跟随鼠标位置进行移动切换

# 语音对话

一、文本输入和语言合成方面:
  使用微软Azure语言模型进行TTS和STT
  可以通过麦克风输入或键入方式，来输入对应文本。

二、语音对话方面：
通过调用OpenAI官方的API来生成回答，并记录。
调取的模型是：gpt-4o-mini

三、文本情感分析方面
使用APISpace的文本情感倾向分析API，对GPT输出文本进行分析

![image](https://github.com/user-attachments/assets/db0a557f-419c-48bb-856d-64c9576220a0)
