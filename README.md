# Record
# The stuffs here show the knowledge I learnt from book.
# All the codes are created by myself and it will keep rolling bigger and bigger as I keep learning coding.
# I started learning C#. 
# Until now(21/1/2018), I have been reading two book and finished reading one of these.
# I start understanding the basic meaning and way to use of the following things(Not everything but the things which are imortant for me).

#   1. Class - It's like category of a being. If you know what class it is, you know how it looks, how it works, etc.
#              Human is a class of human being. We know human being walks by feet, has head, etc.
#              It looks like this : public Class MyClassName{ xxxxxx }
#
#   2. Method - In an easy way to say, you use method to do the stuffs you want to. 
#               Maybe we have a calculation today which is "c = a + b". We can enter the value of a and b, 
#               then method will help us to calculate it.
#               It looks like this : public void MethodNmae() { xxxxxxxxxx }
#
#   3. Variable - It's a container we save value( As the way I keep reading, it's much more than just a container to save value :P )
#                 We could put something in it, then when we need the stuffs are inside the bocontainer, 
#                 we could take the stuff from it. In the example in line 13 "c = a + b". a, b and c are variable.
#                 Of course, different container has different use. We won't use a paper container to keep the water. 
#                 Same in code. Different type of variable saves different kind of value. There are few of examples.
#                 Int save integer(Ex: 123, 999, 209), string save text(Ex: Peter, Ben). 
#                 But how could the computer know what the container could keep? Ans : We need to declare it before we use it.
#                 It looks like this : int varNmae = 777;
#
#   4. Property - For me, it's kind of variable, but it's not totally same as variable.
#									A variable(int) really just for saving a value, but property is more like a transfer satation for a specific variable.
#									We use it to design what to put in variable, and what kind of stuffs we want to send out from variable, 
#									and we could design a property as read-write, read-only, or write-only.
#									Why we need to make it so complicated? Why don't we just use variable?
#									There are several reasons, but the most important reason I believe is changing/reading the variable in a safety way.
#									We could just use private to hide the variable but what if we offen need to change it?
#									What if We just want it to be read-only? 
#									Property can do it easily.
#									It looks like this : public int propertyName { get; set; }
#
#		5. Inheritance - As it's name shows, inheritance. 
#										 It gives a new class a power to chose what ability it wants to inherit from an old class.
#										 We would say the new class as "Child" and the old class as "father"/"base"
#										 It's like a DNA. You are like you parents. 
#										 What is the benefit of doing it? Why don't we just write a new class? 
#										 Most of the information I searched said that it helps us to extent and motify a class.
#										 For example, we create a class that is just for simple calculation(addition and subtraction).
#										 But We want to make a new class that could also able to do multiplication and division.
#										 We don't need to type same code again, we only need to create two new methods for multiplication and division.
#										 So we extent a new class(Child) from an old class(father/base).
#										 It looks like this : public Class FatherClaass { xxx }
#																				  public Class ChildClass : FatherClass { xxx }
#
#		6. Constructor - Create an initiation of a class. If we want to make a special initiation of a class, we use construction to do it.
#										 It allows us to initiate a class when we declare it as a new instance. The construction has a same name as the class
#									 	it looks like this : public Class MyClass 
#																				 {
#																					 	public MyClass() { Your special initiation code }
#																				 }
#
#		7. Destruction - Release the resource that we want to but we couldn't control when to do it. 
#										 It's determined by a system which is called garbage collector.
#
# Written at 21/1/218
#Copyright © GU
