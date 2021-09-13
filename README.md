# AVS3-video-code-stream-analysis-system
此AVS3视频编解码分析系统只适用于HPM-5.1版本得到的码流文件，通过将码流文件导入该码流分析仪中可以实现逐帧播放并进行解析，实现码流的Sequence Header、每一帧的Picture Header、参考帧列表、LCU/CU块划分、运动矢量、预测模式、Affine技术、预测残差等信息的展示与可视化显示功能。

## 使用指南
点击左上角菜单栏“文件”按钮，选择“打开”一栏，在弹出的文件选择窗口中选择所需解码的符合HPM-5.1版本的码流文件或视频文件，若不符合标准会弹出错误提示。之后会弹出要求您输入码流分析的起始帧和结束帧序号的输入栏，默认为第一帧和最后一帧，已在输入栏中默认输入。

**打开码流流程图：**
![image](https://user-images.githubusercontent.com/74785318/133092463-d5eb093d-754c-4a8c-8fab-223471e92719.png)

**解码成功软件界面图（不同分辨率的码流显示情况略有不同）：**
**输入码流分析起始帧序号图（默认0）：**
![738a40d658857762164faa655ff62b77.png](evernotecid://72566A22-9AE2-4E79-91AB-A7D83DCC27E7/appyinxiangcom/27132005/ENResource/p1387)@w=300
**输入码流分析结束帧序号图（默认为该码流文件的最后一帧）：**
![5e72b9d525fc3d591323a2b00eb9039f.jpeg](evernotecid://72566A22-9AE2-4E79-91AB-A7D83DCC27E7/appyinxiangcom/27132005/ENResource/p1388)@w=300

3. 解码过程中会弹窗显示正在解码第几帧（弹窗会自动关闭无需手动），等待解码过程全部结束后即可在功能区获得码流的详细信息展示，具体功能将在下放功能说明部分介绍，若要切换码流请直接重新打开码流文件即可。

**解码成功软件界面图（不同分辨率的码流显示情况略有不同）：**
![image](https://user-images.githubusercontent.com/74785318/133092520-a8cc2557-7975-4939-9946-2da08130b846.png)

