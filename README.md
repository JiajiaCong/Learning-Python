Learning-Python
===============
# python中的数学运算

- 阶乘 import math   math.factorial(5)表示5的阶乘

# 一些小技巧

- raw_input和input的区别

两者的区别可以从下面的这个命令中看出来。raw_input是把输入的东西看成字符串！！

      num=1
      allnum=3
      count=0
      while num<=allnum:
      	grade=input("please give the grade of student"+str(num)+":")
      	if grade>=60:
      		count=count+1
      	else:
      		print("this student fails")
      
      	num=num+1
      
      print(count)
      
      
      num=1
      allnum=3
      count=0
      while num<=allnum:
      	grade=float(raw_input("please give the grade of student"+str(num)+":"))
      	if grade>=60:
      		count=count+1
      	else:
      		print("this student fails")
      
      	num=num+1
      
      print(count)
