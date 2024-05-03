# selectolax-rs
A fast html ripper ported to rust. Now you might be wondering, why would a cython programmer like me want to use this in a language like rust?
If your trying to build a small executable application for someone else to use that needs to be compact, python becomes less of a good choice 
since python lacks the ability to know about cretain strings at compile time and I wanted to see if selectolax would run faster if I tried porting all
of it or as many parts as I want to use in rust. Rust is a fairly newer language that I just recently got around to learning but I wanted to implement 
an html parser that I was most familiar with to help me rip through large sums of html data in a reasonable amount of time. 

