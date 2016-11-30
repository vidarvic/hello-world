# hello-world
first repository
test 
<<<<<<< HEAD

# Chuck is in the house!!!
=======
#Q1
math_pass = {'Tom','John','Mary','Jimmy','Sunny','Amy'}
eng_pass = {'John','Mary','Tony','Bob','Pony','Tom','Alice'}


#數學及格 但英文不及格
#mpenp = math_pass - mpep
me = math_pass | eng_pass
mpenp = me - eng_pass
print(mpenp)

#數學不及格但英文及格
#epmnp = eng_pass - mpep
epmnp = me - math_pass 
print(epmnp)

#數學 英文都及格
mpep = math_pass & eng_pass
print(mpep)



#Q2
#成績list
Tom_list = [80,100,90,95]
print(Tom_list)
John_list = [100,93,75,80]
print(John_list)
#dict
dict = {"Tom":[80,100,90,95],"John": [100,93,75,80]}
print(dict)

#平均分數
T0 = Tom_list[0]
T1 = Tom_list[1]
T2 = Tom_list[2]
T3 = Tom_list[3]
T = T0 + T1 + T2 + T3
Tom_average = T/4
print(Tom_average)

J0 = John_list[0]
J1 = John_list[1]
J2 = John_list[2]
J3 = John_list[3]
J = J0 + J1 + J2 + J3
John_average = J/4
print(John_average)
>>>>>>> refs/remotes/vidarvic/master
