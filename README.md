# python
## 基本函數
!/usr/bin/env python
是為了防止用戶沒有將python裝在默認的路徑。首先會到env設置裡查找python的路徑，再調用編譯器完成操作。

## 算出球表面積與面積

#!/usr/bin/env python

#coding=utf-8

radius = eval(input("Enter a number for radius: "))

area = radius * radius * 3.1415962*4

volume = area * 4

print("半徑", radius, "表面積", area, "體積", volume)

## 算出平均

#!/usr/bin/env python

#coding=utf-8

x,y,z  = eval(input("Enter a number for radius: "))

a=(x+y+z)/3

print("輸入的數值", x, y, z, "平均", a)
