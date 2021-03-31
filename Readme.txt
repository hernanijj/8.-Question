# Question 8 
This question contains the sequence of command necessary to do the following problems:

Problem #1
I have a relation ABC. 

What are the sequence of commands to determine its structure?

Problem #2

I have a relation XYZ. 

Its structure is noted to the right

XYZ =  { file (B1) of } record
  B1   : integer;     { block number   B1
  Name : Char8;       { B1 name
end;   
What are the sequence of commands to read the first and last records of relation XYZ?

Problem #3
Continuing with relation XYZ

What are the seuquence of commands to read key value 10 and the next 2 records?


On cmd type to clone the project
```
https://github.com/hernanijj/8.-Question.git
```

Problem#1
```
-bq rel<ABC> di x
```
Problem#2
```
-bq rel<XYZ> re f re l x
```
Probmlem#3
```
-bq rel<XYZ> key<10> re k re n re n x
```


