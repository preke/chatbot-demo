# SAO demo



## 新需求

1. 更新头像，静态文件已经上传，目前可以正常load， 但是需要调整一下大小，先尝试一下如何改变；（尝试 前端调整大小 or 换更大的其他图片尝试，如果是后者的原因，我们可以跟那边沟通要新图）
2. 探索一下如何改theme (https://docs.botui.org/theme.html)

2021.0517新更新需求
1. 尝试不同形式的T&C,分多段呈现或放一段内（段指的是聊天中一条信息）
2. 在学生选择了suggestion后，仍然有全部suggestion的选项
3. Online Chat T&C 需要再次回答问题包括基本的联系方式以及紧急联系人的联系方式
4. workflow中stop here 那句话下面的一大块句子要用不同的颜色展示
一些需要进一步讨论的问题
1. 有哪些信息需要统计
2. counselor的默认status
3. 如何提醒counselor
4. 如何设置聊天自动退出的条件，比如counselor五分钟内不重连就默认对话结束





## 更新:

- 采用新flow，未使用Pop-up message
- 重新调整响应时间


## 需求：



- 添加头像 参考：https://github.com/botui/botui/issues/81
- 登录信息传回后台，发送请求给ITS认证
- 选择语言（ENG/繁/简体）（是否能够提前为第一个逻辑？）
  

