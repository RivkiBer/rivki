import os
import shutil
from fileinput import close
# 1
os.mkdir("C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder")
# 2
os.rmdir("C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder")
# 3
with open('C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder\\file.txt','w')as file:
    file.write("Hello World")
# 4
with open('C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder\\file.txt','a')as file:
    file.write("rivki")

with open('C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder\\file2.txt','w')as file2:
    file2.write("Hello World")
os.remove("C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder\\file2.txt")
for item in os.listdir("C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder"):
    print(item)

for item in os.listdir("C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder"):
    full_path = os.path.join("C:\\Users\\PC\\Desktop\\Python\\PyCharmMiscProject\\folder", item)
    print(full_path)
