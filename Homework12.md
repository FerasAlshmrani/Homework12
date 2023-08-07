
## 1

![[pngs/png1.png]]

The output is :
```
hey from message1
```

it shows only the System.out.println();

-------------------------------------------------

## 2

![[pngs/png2.png]]

The output is :
```
hey from message1
hey from message2
```
IT HAS TO BE IN THIS ORDER

------------------------------------

## 3

![[pngs/png3.png]]

we don't know who will start first between 
getMessage1() and getMessage3()

but if started getMessage3() the second method will start after that will be getMessage2() for example:

The output is :
```
hey from message3
hey from message2
hey from message1
```
or this output :
```
hey from message1
hey from message3
hey from message2
```

--------------------------------------------
## 4

![[pngs/png4.png]]
![[pngs/png5.png]]


we don't know who will start first between 
getMessage1 and getMessage3

but if started getMessage3() the second method will start after that will be getMessage2() 
and if started getMessage1() the second method should work is MainController() but :
MainController() will NOT RUN because this method don't have bean

for example:

The output is :
```
hey from message1
hey from message3
hey from message2
```
or this output :
```
hey from message3
hey from message2
hey from message1
```

------------------------------

## 5
![[png6.png]]
![[pngs/png7.png]]

we dont know who will start first between 
getMessage1 and getMessage3

but if started getMessage3() the second method will start after that will be getMessage2()
The second class don't have @Bean so it won't run because of it

for example:
the output is :
```
hey from message3
hey from message2
hey from message1
```
or this output :
```
hey from message1
hey from message3
hey from message2
```