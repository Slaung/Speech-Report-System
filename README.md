# 語音報案系統

- Socket: 包含接線員端(Operator)、消防局端(Client)和伺服器端(Server)。
- Task_chatbot: python語音機器人。

目錄：
- 系統架構
- Server、接線員端結構
- 成果圖

## 1. 系統架構
整體系統架構如下：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure7.png)

整體流程圖如下：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure1.png)

Server端功能結構圖：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure8.png)

接線員端功能結構圖：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure9.png)

上傳案件-非重複報案情況(Server端-接線員端)：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure2.png)

上傳案件-重複報案情況(Server端-接線員端)：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure3.png)

查詢未處理案件(接線員端)：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure4.png)

請求派車-成功情況(接線員端)：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure5.png)

請求派車-失敗情況(接線員端)：

![image](https://github.com/Slaung/Speech-Report-System/blob/main/Figure/Figure6.png)
