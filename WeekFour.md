## Week Four
##### What's New
This week I started to tinker with the `AWK` commmand before I left on my school trip to florida, I figured it would be a good thing to start being that there are not so many commands in `AWK`. `AWK` is a language that is designed for processing text, when the programs is running `AWK` each line is broken up into feilds and each line is its own "feild" it was created at Bell Labs
```
`if ( conditional ) statement [ else statement ]
while ( conditional ) statement
for ( expression ; conditional ; expression ) statement
for ( variable in array ) statement
break
continue
{ [ statement ] ...}
variable=expression
print [ expression-list ] [ > expression ]
printf format [ , expression-list ] [ > expression ]
next 
exit`
and played around 
```
##### Take away?
When I was playing around with `awk` is that you can even use it to do easy calculations; like when I was using `awk` to print the squares of numbers one through ten. 

`BEGIN {
	i=1;
	while (i <= 10) {
		printf "The square of ", i, " is ", i*i;
		i = i+1;
	}
	for (i=1; i <= 10; i++) {
		printf "The square of ", i, " is ", i*i;
	}
exit;`


