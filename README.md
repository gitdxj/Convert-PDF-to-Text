# Convert PDF to text

现在确定的方法：
* pdfminer.six
* pdftotext  

其中pdftotext的效果很最好，pdfminer.six对于phone_numbers中第一个文件会有乱码问题，而pdftotext鲁棒性很好。

## 10.30
完成邮件提取  
注意re里面的一个坑：当你用括号把正则表达式的一部分圈出来的时候，re会匹配正则式但调用findall时只会给你返回括号里但字符串