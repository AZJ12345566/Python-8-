# Python-8-
Python学习笔记(8)
# p29 对象的布尔值
#python一切皆对象，所有对象都有一个bool值
print(bool(False)) #False
print(bool(0)) #False
print(bool(0.0)) #False
print(bool(None)) #False
print(bool('')) #False
print(bool("")) #False
print(bool([])) #空列表
print(bool(list())) #空列表
print(bool(())) #空元组
print(bool(tuple())) #空元组
print(bool({})) #空字典
prinit(bool(dict())) #空字典
print(bool(set())) #空集合
print('------------------以上对象的bool值为False-----------------------')
print('------------------其他对象的bool值均为True-----------------------')
print(bool(18))
print(bool(True))
print(bool('helloworld'))



# p30 分支结构_单分支结构
money=1000 #余额
s=int(input('请输入取款金额')) #取款金额
#判断余额是否充足
if money>=s:
   money=money-s
   print('取款成功，余额为:',money)



# p31分支结构_双分支结构
num=int(input('请输入一个整数'))

#条件判断
if num%2==0:
   print(num,'是偶数')
else:
   print(num,'是奇数')
