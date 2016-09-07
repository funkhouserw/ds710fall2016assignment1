
# DS710 Assignment 1
---
#### Wilson Funkhouser, Last modified Tuesday, Sep 6, 2016

---
### (1.0) Open R, check version 

```
> $ R
R version 3.1.2 (2014-10-31) -- "Pumpkin Helmet"
Copyright (C) 2014 The R Foundation for Statistical Computing
Platform: x86_64-unknown-linux-gnu (64-bit)
```
---
### (1.1) Cube Root

```
> 2015^(1/3)
[1] 12.63063

```

---
### (1.2) Abs Value

```
> abs(5.7-6.8)/.58
[1] 1.896552
```

---
### (1.3) Create list

```
> a = 1:12
> a
[1]  1  2  3  4  5  6  7  8  9 10 11 12

```

---
### (1.4) odd numbers

```
> b = c(1, 3, 5, 7, 9, 11)
> b
[1]  1  3  5  7  9 11
```

---
### (1.5) odd numbers 2

```
> c = seq(1,11, 2)
> c
[1]  1  3  5  7  9 11
```

---
### (1.6) LN

```
> ln.a = log(a)
> ln.a
[1] 0.0000000 0.6931472 1.0986123 1.3862944 1.6094379 1.7917595 1.9459101
[8] 2.0794415 2.1972246 2.3025851 2.3978953 2.4849066
```

---
### (1.7 sqrs of odd numbers)

```
> squares  <- seq(1,11,2)
> sq.squares  <- sqrt(squares)
> sq.squares
[1] 1.000000 1.732051 2.236068 2.645751 3.000000 3.316625
```

---
### (1.8) ?sd
```
> ?sd
#[output omitted]
```
 Standard deviation. To quote the manpage itself:
> Description:
>      This function computes the standard deviation of the values in
>      ‘x’.  If ‘na.rm’ is ‘TRUE’ then missing values are removed before
>      computation proceeds.



---
### (1.9) What is your name?

```
> name  <-  "Wilson"
> paste("My name is", name)
[1] "My name is Wilson"
```
