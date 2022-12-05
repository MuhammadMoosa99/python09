# python09
import pickle

class student:
    def getdata(self):
        self.name="Aman"
        self.rollno=30
    def putdata(self):
        print("Name=",self.name)
        print("Rollno=",self.rollno)

s= student()
f=open("data.dat","wb")

pickle.dump(s,f)
f.close()

s1=('id':12212,'name':'aman','marks':45)
s2=('id':12234,'name':'john','marks':35)
s3=('id':12235,'name':'poup','marks':98)

db=[s1,s2,s3]
