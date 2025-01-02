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

# 唱歌
根据不同性别小猫设定不同演唱的歌曲
同时为了增强表现效果，通过编写脚本，使得小猫能够跟随音乐进行摇摆、口型匹配

![image](https://github.com/user-attachments/assets/f555b76b-4c4e-4f5d-8f4c-57f39728fbd4)

![image](https://github.com/user-attachments/assets/7f1e701b-e973-4bf8-9cd2-3b9a1d20e831)

# 讲故事
通过TTS来进行故事的阅读
同样的，为了增强效果，我们增加了Live2D模型动画，让小猫先阅读书籍后进行故事的阅读

![image](https://github.com/user-attachments/assets/ff11729f-3259-48de-9c56-4852fc201b10)

![image](https://github.com/user-attachments/assets/6519d3ff-8014-4c5f-a37f-0c49f7e2095f)

# 换装

![image](https://github.com/user-attachments/assets/6a510554-5001-4d9c-a0ff-0351f3b0f47f)

![image](https://github.com/user-attachments/assets/d5b96cff-f430-4796-b4f6-5e9ba0d45f0c)

# 小猫投喂和好感度系统

![image](https://github.com/user-attachments/assets/3a9ec149-0cec-44c5-8502-024838a3c28b)

![image](https://github.com/user-attachments/assets/4db761cf-106e-4055-ae2c-5e699a45e65b)

![image](https://github.com/user-attachments/assets/bc713f39-ceda-4bf8-974c-a78c000f3267)

# 聊天记录框（目前显示最近的两条信息）

![image](https://github.com/user-attachments/assets/1af67e54-0db1-4e31-a835-59cae6151533)


