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

```

