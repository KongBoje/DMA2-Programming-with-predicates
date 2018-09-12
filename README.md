# DMA2-Programming-with-predicates

1. [Install Prolog](http://www.swi-prolog.org/download/stable)
2. Download file [student_calendar.pl](https://github.com/KongBoje/DMA2-Programming-with-predicates/blob/master/student_calendar.pl) from this repository
3. Run file through prolog cmd. 

- first you have to consult with the file like this:
``
make.
``

- and then execute following Queries:

``
?- school(mon,r1,c1,X). 
``

or

``
?- school(fri,r2,c2,X).
``

- When it runs you only get one student at the start, for it to run through the whole query you have to press ";" at the end of each student, like this:

```
?- school(mon,r1,c1,X).
X = bob ;
X = max ;
X = liz.
```
