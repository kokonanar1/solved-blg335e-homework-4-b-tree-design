Download Link: https://assignmentchef.com/product/solved-blg335e-homework-4-b-tree-design
<br>
Part 1: B-Tree Design

In this homework, we will work on B-trees. We have a simple node structure having the following three attributes:

<ul>

 <li><strong>int </strong>x</li>

 <li><strong>int </strong>y</li>

 <li><strong>char </strong>z</li>

</ul>

Create a node structure to store these attributes in addition to other pointer attributes to create the tree. Then, create the tree according to the given inputs. Here the first input indicates the total node count, second input indicates degree of the tree, the third input indicates which attribute should be used as the key. The other inputs are to assign x,y and z values respectively. An example input is given below.

1

<em>BLG335E – Analysis of Algorithms I                      2020-2021 Fall                 Homework-4</em>

<table width="564">

 <tbody>

  <tr>

   <td width="564">21 3 z56 34 G71 6 M68 0 P123 −666 T999 4 X 41 33 A−66 8 B748 54 C 99 978 D400 23 E98 66 J0 43 K66 12 N45 1 O11 −34 Q67 −36 R40 7 S85 3 U 8 2 V62 9 Y9 5 Z</td>

  </tr>

 </tbody>

</table>

1

3

5

7

9

11

13

15

17

19

21

23

The output for the input above should be a traverse of the tree in prefix order. Every node should be written in a different line.

<table width="564">

 <tbody>

  <tr>

   <td width="564">(748 ,54 ,C) (56 ,34 ,G) (68 ,0 ,P) (40 ,7 ,S) (8 ,2 ,V) (41 ,33 ,A) (−66,8,B)(99 ,978 ,D) (400 ,23 ,E)(98 ,66 ,J) (0 ,43 ,K) (71 ,6 ,M) (66 ,12 ,N) (45 ,1 ,O)(11,−34,Q) (67,−36,R) (123,−666,T) (85 ,3 ,U)(999 ,4 ,X) (62 ,9 ,Y) (9 ,5 ,Z)</td>

  </tr>

 </tbody>

</table>

2

4

6

Compare your outputs with the outputs from HackerRank. For full grades, you should obtain true outputs for each of the cases.

<h2>2 – Part 2: Delete Operation</h2>

In this part, another line is added to the input file containing information of which key should be deleted from the tree. After creating the tree, delete the given key from the tree and print the tree as you have done in the previous part.

<h2>3 – Part 3: ”What if…”</h2>

Using at most 500 characters in a txt file, answer the following questions.

2

<ul>

 <li>Suppose that, using the same structure, we created three different bonds according to different x,y, z values. Thus, for every node we have the information of <em>x children</em>, <em>y children</em>, <em>z children </em>and <em>x parent</em>, <em>y parent</em>, <em>z parent </em> What is the complexity of insertion operation for this structure?</li>

 <li>Suppose that, instead of storing x,y,z values in a node, our B-tree has a different node structure containing mini B-Trees as given in Figure 1. The key of each node for the tree is calculated as standard deviation of x values inside the mini B-tree. What is the complexity of adding a new node to one of the mini B-trees?</li>

</ul>

Figure 1: Mini B-Trees inside another B-tree

3