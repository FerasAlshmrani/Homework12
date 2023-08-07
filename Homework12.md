
## 1

![[Pasted image 20230807134354.png]]

The output is :
```
hey from message1
```

it shows only the System.out.println();

-------------------------------------------------

## 2

![[Pasted image 20230807134536.png]]

The output is :
```
hey from message1
hey from message2
```
IT HAS TO BE IN THIS ORDER

------------------------------------

## 3

![[Pasted image 20230807134836.png]]

we don't know who will start first between 
getMessage1() and getMessage3()

but if started getMessage3() the second method will start after that will be getMessage2() for example:

The output is :
```
hey from message3
hey from message2
hey from message1
```

--------------------------------------------
## 4

![[Pasted image 20230807134920.png]]
![[Pasted image 20230807134927.png]]


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

------------------------------

## 5
![[Pasted image 20230807135044.png]]
![[Pasted image 20230807135051.png]]

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