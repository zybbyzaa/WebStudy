##  Markdown语法参考

1.  标题

        # 一级标题h1（最多六个#，代表h6）
        
        一级标题
        ===================
        
        二级标题
        --------------------

2.  引用

        >引用内容
        >>引用嵌套

3.  代码

        `code`(无排版)
        
        换行并空4个空格以上(保留排版格式)

4.  图片

        行内式
        ![altText](url "title")
        
        参考式
        [altText][id]
        [id]: url "title"

5.  链接
      
        行内式
        [Text](url "title")
      
        参考式
        [Text][id]
        [id]: url "title"
        
        
6.  列表

        有序列表
        1. 有序列表
        
        无序列表
        +/-/*  无序列表
        
7.  换行

        行尾输入两个或以上的空格，然后回车，可插入一个<br/>
        
8.  强调

        *斜体*
        **粗体**
        ***斜粗体***
  
9.  水平分隔线

        ***
        ---
  
10. 转义字符

        Markdown 可以利用反斜杠来插入一些在语法中有其它意义的符号
        如：\ ` + - * _ # . ! () {} []
