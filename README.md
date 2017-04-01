# hello-world
This is Abrar!

Edit more!


add more details!


# Markdown (#)
## Markdown (##)
### Markdown (###)


# Lists

* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
  

```php
data _null_;

		do i= 1 to 100;
			if mod(i,3) =0 then put i & 'Fuzz';
			else if mod(i,5) =0  then put i & 'Buzz';

		end;
run;

```


9709  data _null_;
9710
9711          do i= 1 to 100;
9712              if mod(i,3) =0 then put i & 'Fuzz';
9713              else if mod(i,5) =0  then put i & '- Buzz';
9714		  else put i=;
9715          end;
9716  run;


##the result:
```php
9717  data _null_;
9718
9719          do i= 1 to 100;
9720              if mod(i,3) =0 then put i & 'Fuzz';
9721              else if mod(i,5) =0  then put i & 'Buzz';
9722              else put i=;
9723          end;
9724  run;

i=1
i=2
3 Fuzz
i=4
5 Buzz
6 Fuzz
i=7
i=8
9 Fuzz
10 Buzz
i=11
12 Fuzz
i=13
i=14
15 Fuzz
i=16
i=17
18 Fuzz
i=19
20 Buzz
21 Fuzz
i=22
i=23
24 Fuzz
25 Buzz
i=26
27 Fuzz
i=28
i=29
30 Fuzz
i=31
i=32
33 Fuzz
i=34
35 Buzz
36 Fuzz
i=37
i=38
39 Fuzz
40 Buzz
i=41
42 Fuzz
i=43
i=44
45 Fuzz
i=46
i=47
48 Fuzz
i=49
50 Buzz
51 Fuzz
i=52
i=53
54 Fuzz
55 Buzz
i=56
57 Fuzz
i=58
i=59
60 Fuzz
i=61
i=62
63 Fuzz
i=64
65 Buzz
66 Fuzz
i=67
i=68
69 Fuzz
70 Buzz
i=71
72 Fuzz
i=73
i=74
75 Fuzz
i=76
i=77
78 Fuzz
i=79
80 Buzz
81 Fuzz
i=82
i=83
84 Fuzz
85 Buzz
i=86
87 Fuzz
i=88
i=89
90 Fuzz
i=91
i=92
93 Fuzz
i=94
95 Buzz
96 Fuzz
i=97
i=98
99 Fuzz
100 Buzz
NOTE: DATA statement used (Total process time):
      real time           0.04 seconds
      cpu time            0.04 seconds





```

