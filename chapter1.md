# First Chapte

* a
* dkfjdk

# title

```
class Desc:
    def __init__(self):
        print('__init__')
        self.data="data"
    def __get__(self, instance, owner):
        print('__get__')
        print('self in Desc: %s ' % self )
        print(self, instance, owner)
        return self.data
    def __set__(self, instance, value):
        print('__set__')
        self.data=value
        print(self,instance,value)
    def __delete__(self, instance):
        print('__del__')
        del self.data
        print(self,instance)
```
dfdf
dfdf
* do
* aa






