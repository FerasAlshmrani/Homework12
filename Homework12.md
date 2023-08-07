
## 1

![png1](https://github.com/FerasAlshmrani/Homework12/assets/101283810/3ed53b4a-53f6-4437-9456-cb7d4d57b5e2)

The output is :
```
hey from message1
```

it shows only the System.out.println();

-------------------------------------------------

## 2

![png2](https://github.com/FerasAlshmrani/Homework12/assets/101283810/759deeb4-8bf4-44fe-949f-654bb3898a23)

The output is :
```
hey from message1
hey from message2
```
IT HAS TO BE IN THIS ORDER

------------------------------------

## 3

![png3](https://github.com/FerasAlshmrani/Homework12/assets/101283810/fc2ccdb2-c45d-4990-8d41-e0b1e1b73ef1)

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

![png4](https://github.com/FerasAlshmrani/Homework12/assets/101283810/8118888d-1edc-4591-a2ee-f9a0085f17bb)
![png5](https://github.com/FerasAlshmrani/Homework12/assets/101283810/a8916e89-4622-4ed4-b365-1995bac21de3)

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

![png6](https://github.com/FerasAlshmrani/Homework12/assets/101283810/e4581c25-cf3e-49b3-8151-3eae344dfb3a)
![png7](https://github.com/FerasAlshmrani/Homework12/assets/101283810/48a91e51-519d-4f50-bef1-7b3d05ba0e7b)

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
