# [B] Evaluate the following expressions and show their hierarchy.



    (a)	ans = 5 * b * b * x - 3 * a * y * y - 8 * b * b * x + 10 * a * y ;
    	(a = 3, b = 2, x = 5, y = 4 assume ans to be an int)

`ans` = `5*b*b*x` - `3*a*y*y` - `8*b*b*x` + `10*a*y;`

`ans` = `5*2*2*5` - `3*3*4*4` - `8*2*2*5` + `10*3*4;`

`ans` = `10*2*5` - `3*3*4*4` - `8*2*2*5` + `10*3*4;`

`ans` = `20*5` - `3*3*4*4` - `8*2*2*5` + `10*3*4;`

`ans` = `20*5` - `3*3*4*4` - `8*2*2*5` + `10*3*4;`

`ans` = `100` - `9*4*4` - `8*2*2*5` + `10*3*4;`

`ans` = `100` - `36*4` - `8*2*2*5` + `10*3*4;`

`ans` = `100` - `144` - `8*2*2*5` + `10*3*4;`

`ans` = `100` - `144` - `16*2*5` + `10*3*4;`

`ans` = `100` - `144` - `32*5` + `10*3*4;`

`ans` = `100` - `144` - `160` + `10*3*4;`

`ans` = `100` - `144` - `160` + `30*4;`

`ans` = `100` - `144` - `160` + `120;`

`ans = -84;`

​    

    (b)	res = 4 * a * y / c - a * y / c ;
    	(a = 4, y = 1, c = 3, assume res to be an int)

`res` = `4*a*y/c` - `a*y/c;`

`res` = `4*4*1/3` - `4*1/3`;

`res` = `16*1/3` - `4*1/3`;

`res` = `16/3` - `4*1/3;`

`res` = `5` - `4*1/3;`

`res` = `5` - `4/3;`

`res` = `5` - `1;`

`res = 4;`

​    

    (c)	s = c + a * y * y / b ;
    	(a = 2.2, b = 0.0, c = 4.1, y = 3.0, assume s to be an float)

`s` = `c` + `a*y*y/b;`

`s` = `4.1` + `2.2 * 3.0 * 3.0 / 0.0;`

`s` = `4.1` + `6.6 * 3.0 / 0.0;`

`s` = `4.1` + `19.80 / 0.0;`

`Error : Cannot divide by 0.0`

​    

    (d)	R = x * x + 2 * x + 1 / 2 * x * x + x + 1 ;
    	(x = 3.5, assume R to be an float)

`R` = `x*x` + `2*x` + `1/2*x*x` + `x` + `1`; 

`R` = `3.5*3.5` + `2*3.5` + `1/2*3.5*3.5` + `3.5` + `1`; 

`R` = `12.25` + `2*3.5` + `1/2*3.5*3.5` + `3.5` + `1`; 

`R` = `12.25` + `7.0` + `1/2*3.5*3.5` + `3.5` + `1`; 

`R` = `12.25` + `7.0` + `0*3.5*3.5` + `3.5` + `1`; 

`R` = `12.25` + `7.0` + `0*3.5` + `3.5` + `1`; 

`R` = `12.25` + `7.0` + `0` + `3.5` + `1`; 

`R = 23.75`

