# cs2102-tutorial-5--sql-part-3-week-7-solved
**TO GET THIS SOLUTION VISIT:** [CS2102 Tutorial #5- SQL (Part 3) Week 7 Solved](https://www.ankitcodinghub.com/product/cs2102-solved-8/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117763&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2102  Tutorial #5- SQL (Part 3) Week 7 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1 Discussions

The following questions are to be discussed during tutorial. All answers will be released with explanation.

1. (Equivalence) Consider the following relational schema:

CREATE TABLE R ( a INTEGER PRIMARY KEY, b INTEGER,

c INTEGER

);

CREATE TABLE S ( x INTEGER PRIMARY KEY,

y INTEGER REFERENCES R(a)

);

1

2

3

4

5

6

7

8

9

10

(a) Q

1

2

3

(b) Q

1

2

3

4

Answer each of the following queries using SQL. For parts (a) to (e), remove duplicate records from all query results.

1

(a) Find the most expensive pizzas and the restaurants that sell them (at the most expensive price). Do NOT use any aggregate function in your answer.

(b) Find all restaurant pairs (R1,R2) such that the price of the most expensive pizza sold by R1 is higher than than that of R2. Exclude restaurant pairs where R2 do not sell any pizza.

(c) For each restaurant that sels some pizza, find the restaurant name and the average price of its pizzas if its average price is higher than $22. Do NOT use the HAVING clause in your answer.

(d) For each restaurant R that sells some pizza, let totalPrice(R) denote the total price of all the pizzas sold by R. Find all pairs (R,totalPrice(R)) where totalPrice(R) is higher than the average of totalPrice() over all the restaurants.

(e) Find the customer pairs (C1,C2) such that C1 &lt; C2 and they like exactly the same pizzas. Exclude customer pairs that do not like any pizza. Do NOT use the EXCEPT operator in your answer.

2 Challenge

The answers to the following questions is given without explanation. Please discuss them on Canvas.

1. (CTE) Consider the following ER diagram.

We assume that we have the following schema:

• Lecturers(id, name, did)

• Profs(id, major)

• Deans(id)

• Departments(did, dname, id)

We say that a dean is important if the dean heads a department where either:

• There are at least 20 professors working in the department excluding the dean, OR

• There are at least 5 professors with di↵erent majors working in the department

Page 2

2. (Universal Quantification) Consider the following schema:

CREATE TABLE Students ( matric VARCHAR(9) PRIMARY KEY, sname VARCHAR(50)

);

CREATE TABLE Projects ( pid VARCHAR(9) PRIMARY KEY,

pname VARCHAR(50)

);

CREATE TABLE Workings ( pid VARCHAR(9) REFERENCES Projects(pid),

PRIMARY KEY(pid, matric) );

CREATE TABLE Category ( pid VARCHAR(9) REFERENCES Projects(pid),

cname VARCHAR(9),

PRIMARY KEY(pid, cname) );

1

2

3

4

5

6

7

8

9 10

11

12

13

14

15

16

17

18

19

Find all pair of distinct projects’ pid(p1, p2) such that the two projects have exactly the same set of categories.

Page 3
