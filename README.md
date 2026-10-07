# 2026
# # # # #14.1
# # # # import math as m
# # # # def kvadrat_tenglama(a,b,c):
# # # #     d=b**2-4*a*c
# # # #     if a!=0:
# # # #         if d<0:
# # # #             print("bo'sh to'plam")
# # # #         elif d>0:
# # # #             x1=(-b-m.sqrt(d))/(2*a)
# # # #             x2=(-b+m.sqrt(d))/(2*a)
# # # #             print("1-yechim:",x1)
# # # #             print("2-yechim:",x2)
# # # #         elif d==0:
# # # #             x=(-b)/(2*a)
# # # #             print("yechim:",x)
# # # #     else:
# # # #         print("bu kvadrat tenglama emas!!!")
# # # # a=float(input("1-koeffitsient:"))
# # # # b=float(input("2-koeffitsient:"))
# # # # c=float(input("ozod xadi:"))
# # # # kvadrat_tenglama(a,b,c)
# # # #14.2
# # # import random as rnd
# # # son=rnd.randint(1,10)
# # # taxmin=int(input("Taxminingizni kiriting:"))
# # # if taxmin==son:
# # #     print("Siz yutdingiz!!!",son)
# # # else:
# # #     print("Keyingi safar omadingiz keladi, taxminiy son=", son)
# # # 14.3
# # from datetime import date, timedelta
# # bugun=date.today()
# # tk=bugun+timedelta(days=100)
# # print("Bugun:",bugun)
# # print("100 kundan keyin:",tk)
# #14.4
import os
papka=input("qaysi papka:")
son=0
for i in os.listdir(papka):
    yol=os.path.join(papka,i)
    if os.path.isdir(yol):
        son+=1
print("papkalar soni:",son)
# #14.5
# import sys
