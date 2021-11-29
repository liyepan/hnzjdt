# 河南宗教自动答题 1.6   重要高质量更新！
### 最近更新 2021-11-30      V1.6
更新内容：

       1、重构了题目匹配机制，匹配成功率高达99.9%   【由之前的模糊匹配改为精准匹配，效果惊人】
       
       2、解决了不同题的题目相同导致答案无法匹配的bug 【如：下列选项正确的是() 。这类题型可以完美匹配】
       
       3、完善了在线题库
       
       4、上传了答题的html页面，下载后自行修改examination.js中的第119行 可以实现点击提交按钮显示自定义分数，然后截图交了
       
       5、windows可执行文件版本同步更新至v1.6
       
    
       
### 注：如果报错【{success:0,msg:'非法操作，涉嫌刷题1'}】  自行查看自己的IP地址是不是河南范围，一定要是河南范围，不要挂梯子！！
       
       

#### 介绍
河南宗教自动答题,完成自动提交试题，经测试，得分均稳定在90以上，可以自行部署到云函数上，或者action，每天自动执行更省心，

#### 目录结构
-tool [工具目录]

    - dealData.py [文本处理]
    
    - driver.py [操作手]
    
    - fuzz.py [答案匹配]
    
-control.py [入口程序]



#### 使用说明
源码版本：
	编辑control.py，填入自己的信息，python control.py运行即可

exe版：
         双击运行


#### 题库项目 最近更新2021-11-28
 题库项目地址 https://github.com/aqz236/aqz236-hnzjtk
