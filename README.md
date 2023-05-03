Download Link: https://assignmentchef.com/product/solved-cs204-advanced-programming-homework-1-word-placement-in-matrix
<br>
Sample Runs

Some sample runs are given below, but these are not comprehensive; therefore, you must consider <strong>all possible cases</strong> to get full mark.

You do not need to give the output exactly as in the sample runs, provided that your output is understandable and clear.

<strong>Sample Run 1: </strong>

Please enter the name of the file: <strong><em>test</em></strong>

File name is incorrect, please enter again: <strong><em>test1</em></strong>

File name is incorrect, please enter again: <strong><em>test.txt </em></strong>

File name is incorrect, please enter again: <strong><em>test1.txt</em></strong>




“sample” was put into the matrix with given starting point: 0,0

direction: r   orientation: CW

s       a       m       p       l –       –       –       –       e

<ul>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

</ul>




“puzzle” could not be put into the matrix with given starting point:

0,1   direction: d   orientation: CW s       a       m       p       l –       –       –       –       e

<ul>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

</ul>




“puzzle” was put into the matrix with given starting point: 1,1   direction: l   orientation: CW s       a       m       p       l u       p       e       –       e z       z       l       –       – –       –       –       –       –

<ul>

 <li>– –       –       –</li>

</ul>




“apple” was put into the matrix with given starting point: 3,2   direction: d   orientation: CCW s       a       m       p       l u       p       e       –       e z       z       l       –       – –       –       a       –       e

<ul>

 <li>– p       p       l</li>

</ul>




“four” was put into the matrix with given starting point: 3,0   direction: u   orientation: CCW s       a       m       p       l u       p       e       –       e z       z       l       –       – f       r       a       –       e o       u       p       p       l




“one” could not be put into the matrix with given starting point: 2,3   direction: r   orientation: CW s       a       m       p       l u       p       e       –       e z       z       l       –       – f       r       a       –       e o       u       p       p       l




“one” was put into the matrix with given starting point: 1,3   direction: r   orientation: CW

s       a       m       p       l u       p       e       o       e z       z       l       n       e f       r       a       –       e o       u       p       p       l




“a” was put into the matrix with given starting point: 3,3   direction: l   orientation: CW s       a       m       p       l u       p       e       o       e z       z       l       n       e f       r       a       a       e

o       u       p       p       l

<strong>Sample Run 2: </strong>

Please enter the name of the file: <strong><em>test2.txt </em></strong>




“fructosamine” was put into the matrix with given starting point: 1,2   direction: r   orientation: CCW a       s       o       t       c m       i       f       r       u –       n       e       –       –




“cryptoxanthin” could not be put into the matrix with given starting point: 0,0   direction: l   orientation: CW a       s       o       t       c m       i       f       r       u –       n       e       –       –




<strong>Sample Run 3: </strong>

Please enter the name of the file: <strong><em>test3.txt</em></strong>




“fructosamine” could not be put into the matrix with given starting point: 1,0   direction: r   orientation: CCW

<ul>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

 <li>– –       –       –</li>

</ul>




“fructosamine” was put into the matrix with given starting point: 1,0   direction: r   orientation: CW –       –       –       –       – f       r       u       c       t –       –       –       –       o –       –       –       –       s e       n       i       m       a




“trouble” could not be put into the matrix with given starting point:

0,0   direction: r   orientation: CW –       –       –       –       – f       r       u       c       t –       –       –       –       o –       –       –       –       s e       n       i       m       a




“trouble” was put into the matrix with given starting point: 2,2   direction: r   orientation: CW –       –       –       –       – f       r       u       c       t e       –       t       r       o l       b       u       o       s e       n       i       m       a




<strong>Sample Run 4: </strong>

Please enter the name of the file: <strong><em>test4.txt </em></strong>




“a” was put into the matrix with given starting point: 0,0   direction: l   orientation: CW a

<strong>Sample Run 5: </strong>

Please enter the name of the file: <strong><em>test5.txt</em></strong>




Invalid input for direction! Direction:  qsd




Invalid input for direction! Direction:  q




Starting point is out of range! Point:  3,1




Starting point is out of range! Point:  -1,1




Starting point is out of range! Point:  1,-1




Starting point is out of range! Point:  1,3




Invalid input for orientation! Orientation: CCWW




Invalid input for orientation! Orientation: 123




Invalid line! Number of values is different than 5.




Invalid line! Number of values is different than 5.




Invalid line! Number of values is different than 5.




Starting point is out of range! Point:  -1,-2




“trueInput” was put into the matrix with given starting point: 0,0   direction: l   orientation: CW t       r       u n       I       e p       u       t

<strong>Sample Run 6: </strong>

Please enter the name of the file: <strong><em>test6.txt</em></strong>




Invalid number for row and/or column!

<strong>Sample Run 7: </strong>

Please enter the name of the file: <strong><em>test7.txt </em></strong>




“therefore” could not be put into the matrix with given starting point: 0,1   direction: r   orientation: CW

–       –       –       –       –       –       –       –       –

“therefore” was put into the matrix with given starting point: 0,8   direction: r   orientation: CW e       r       o       f       e       r       e       h       t

<strong>Sample Run 8: </strong>

Please enter the name of the file: <strong><em>test8.txt </em></strong>







“therefore” was put into the matrix with given starting point: 8,0   direction: r   orientation: CCW e r o f e r e h t








