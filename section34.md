# 3.4 细节设计

这款App有一些贴心的细节设计。首先，考虑到国外学校的名称全称较长，在条目显示栏容易导致文字分行显示，App设计了根据学校名称长短自动调整字号的功能，当学校的名称超过15个字符后，字体将自动减少至20号，便于界面显示的美观。

根据用户反馈，第二个屏幕在信息填写完毕后点击保存按钮后系统没有提示，容易认为没有保存成功。因此添加了点击后弹出“保存成功”这一提示信息的功能，提升用户体验。

另外，在第三个屏幕点击编辑功能重新编辑项目信息时，返回到的第二个屏幕将自动读取已经录入的信息。这样使用者只需要更改自己希望更改的信息即可，无须重新录入所有信息，这极大的简化用户的操作过程。