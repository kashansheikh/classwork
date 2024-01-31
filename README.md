
'''class Bike:
    name = ""
    gear = 0
    clutch = 0
bike1 =Bike()
bike1.gear = 11
bike1.name = "Mountain Bike"
bike1.clutch= 1
print(f"name: {bike1.name}, Gears: {bike1.gear},clutch: {bike1.clutch}")'''
          




'''class Human:
    attr1="human"
    attr2="student"
    def fun(self):
        print("I'm a",self.attr1)
        print("i'm a",self.attr2)
rodger=Human()
print(rodger.attr1)
rodger.fun()'''

'''class python:
    def __init__(self,name,company):
        self.name=name
        self.company=company

def show(self):
    print("Hello my name" +self.name+"and I"+ "work in"+self.company+".")

obj=python("kashan","bano qabil")
obj.show()'''


# Sample class with init method
'''class Person:
	# init method or constructor
	def __init__(self, name):
		self.name = name
	# Sample Method
	def say_hi(self):
		print('Hello, my name is', self.name)
p = Person('Ghufran')
p.say_hi()'''


'''class Room:
    length = 0.0
    breath = 0.0
    
    def calculate_area(self):
        print("Area of Room =", self.length * self.breath)
        study_room=Room()
        study_room.length = 42.5
        study_room.breath = 30.8
        study_room.calculate_area()'''

class Employee:
    __id=0
    __name=""
    __gender=""
    __city=""
    __salary=0
    def setData(self):
        self.__id=int(input("Enter Id:\t"))
        self.__name = input("Enter Name:\t")
        self.__gender = input("Enter Gender:\t")
        self.__city = input("Enter City:\t")
        self.__salary = int(input("Enter Salary:\t"))
    def showData(self):
        print("Id\t\t:",self.__id)
        print("Name\t:", self.__name)
        print("Gender\t:", self.__gender)
        print("City\t:", self.__city)
        print("Salary\t:", self.__salary)


def main():
    #Employee Object
    emp=Employee()
    emp.setData()
    emp.showData()

if __name__=="__main__":
    main()
