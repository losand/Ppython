十大歌手
=======
为了丰富校园生活，学校拟组织一场歌手大赛，从参赛选手中选拔出10名相对突出的学生  
由**十名**评委打分  

计算得分**打分的平均分**去掉最低和最高  

可以看出至少需要两组数组**学生**，**评委**

    student=[]
    score=[0,0,0,0,0,0,0,0,0,0]
    for score in range(10)
rnm 垃圾python
     score = []
AllScore=0
for i in range(1,9):
   s= input(f"{i}Input: \n")
   score.append(s)
print("依次为",score)
print("The Max",max(score))
print("The Min",min(score))
score.remove(max(score))
score.remove(min(score))
print(score)
n= len(score)
print(n)

print(AllScore/(len(score)))
    
