# test
If you want to test erlang code of this repoisentery you may need to use [TC](https://github.com/wudixiaotie/algorithm/blob/master/erlang/tc.erl).  
TC is an erlang module for evaluate an erlang function  and measures the elapsed real time.  
It can do concurrency test by use tc:ct(M, F, C, N), N is how many processes you want to spawn.  
And also do Sequential test by use tc:t(M, F, C, N), N is how many times you want to run function.