# rpp-t

#### rpp-t is RandomPlusPLus Tools. So to speak, an extension for the random module

</br>

#### Package functions:

</br>

#### the first function
the first thing I started with was ```Rlist```</br>
it makes it easier to write code to randomize the list by 9.5 times.

```
import rppt

rppt.Rlist([1,2,3,4,5,6,7,8,9], [1,2,3])# <---------+ 
# here for randomization ^                          | 
# and here that these symbols would be an exception +
# you can also choose not to enter a list of exceptions.
```

#### ```Rlist``` has a total of 8 functions. let's go through them too!

```myRandomList = rppt.Rlist([1,2,3,4,5])``` - since 'Rlist` is a class, it can be assigned</bt>
to a variable

1. ```myRandomList.Rlist()``` - changes values

2. ```myRandomList.AppendMainList([6,7,8])``` - adds numbers from the argument to the list

3. ```myRandomList.AppendBlackList([1,3,5])``` - adds a blacklist

4. ```myRandomList.SetSeed('seed')``` - changes the seed of generation

5. ```myRandomList.SetOutput('4')``` - changes the output

6. ```myRandomList.GetMainList('list/str')``` - displays the main list you can set the type:</br>
list or str, or you can not set

7. ```myRandomList.GetBlackList('list/str')``` - displays the blacklist you can set the type:</br>
list or str, or you can not set

8. ```myRandomList.GetList('list/str')```- displays a list without items that are in the blacklist</br>
you can set the type: list or str, or you can not set


#### at the moment, the functions of the library ```rppt``` are completed.
#### but it is updated every day. don't miss it and keep an eye on this page!
