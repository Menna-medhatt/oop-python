# oop-python
#base class
class Animal :
  def _init_(self,name):
    self.name=name

  def eat(self):
    print("the animal is eating")
  def sleep(self):
    print("the animal is sleeping")

#inheritance
class dog(Animal):
  #polymorphism
  def eat(self): 
    print("the dog is eating")
  def bark(self):
    print("the animal is barking")

#inheritance
class cat (Animal):
   #polymorphism
  def eat(self):
    print("the cat is eating")
  def meow(self):
    print("the animal is meowing")

dog1=dog()
cat1=cat()
dog1.bark()
cat1.meow()
dog1.eat()
dog1.sleep()
cat1.sleep()
cat1.eat()
