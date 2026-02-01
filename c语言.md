### 学习笔记
+、-、*与数学中的使用方法相同

/(除)：当符号两边都是整数类型时，会执行整数除法返回商(整数类型)(被除数、除数、商、余数)；当符号两边有任意一边为浮点数，则执行浮点数除法返回商(浮点数类型)(被除数、除数、商)

%(取余)：规定符号两边只能是整数类型，根据上面的整数和浮点数除法就能看出，如果是浮点数除法则没有余数的地方，则不会产生余数


### 错题总结
<img width="540" height="105" alt="image" src="https://github.com/user-attachments/assets/aad2ad81-1b42-4c41-8751-6c4365576ace" />

答案：%(解析在上边)

<img width="295" height="96" alt="image" src="https://github.com/user-attachments/assets/c20ee13b-0932-44db-bfe9-b9db4031b4f6" />

答案：使位置指针重新返回文件的开头(没学到)

<img width="855" height="93" alt="image" src="https://github.com/user-attachments/assets/986fc122-c073-4d93-aba1-1abc41e15e01" />

答案：a/a != 0

解析：题目的意思是如何写a的表达式才能够满足a不等于0为真值；      a != 0显而易见；     a则是因为在c语言中，0为假值，非0为真值。if在判断a的时候非0进入，0则跳过也符合题意的要求a不等于0。

<img width="425" height="265" alt="image" src="https://github.com/user-attachments/assets/f68fe4e0-49d9-4474-a8d7-6faf58c244d8" />

答案：7(没学到+解析不理解)

<img width="350" height="206" alt="image" src="https://github.com/user-attachments/assets/4e112770-6d51-4f28-9239-893836eb129b" />

答案：3(知道||的用法，但是只在判断中使用过，理解不够透彻)

解析：前++是先自增然后再运算。因为||是短路或。只要符号前面的为真，符号后面的就不会执行；前面的变量值经过前++计算后为4，为真，因此直接短路，不执行符号后面的，故后面的变量值不变






