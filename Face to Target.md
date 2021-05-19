# hi 
``` python
class Car:
    wheels =4
    def drive(self):
        print("行驶")


car =Car()
print(Car.wheels)
print(car.wheels)
Car.wheels = 3
print(Car.wheels)
print(car.wheels)
car.wheels = 4
print(Car.wheels)
print(car.wheels)
```
类方法

``` python
class Bus:
    @classmethod
    def stop(cls): #类方法
       print("类方法")
bus = Bus()
bus.stop() #通过类方法调用类
Bus.stop() #通过类调用类
```

``` python
class Bus:
    @staticmethod
    def stop(cls): #方法
       print("类方法")
bus = Bus()
bus.stop() 
Bus.stop() 
```
