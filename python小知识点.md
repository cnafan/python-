# 小结
time.strftime('%Y-%m-%d',time.localtime(time.time()))

>%y 两位数的年份表示（00-99）  

>%Y 四位数的年份表示（000-9999）  

>%m 月份（01-12）  

>%d 月内中的一天（0-31）  

>%H 24小时制小时数（0-23）   

>%I 12小时制小时数（01-12）  

>%M 分钟数（00=59）   

>%S 秒（00-59） 

---
# 文件操作  

    with open('file.txt','r') as f:  
    
      lines=f.read()  
      
    for line in lines:  
    
      line.rstrip()    
      
---  
# python3 打包  
    pyinstaller -F C:\weather.py
  F 参数是打包为单文件
