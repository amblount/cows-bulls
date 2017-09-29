# cows & bulls

Hey, I forgot to send you my tips for that coding challenge


[7:48] 
So the first thing to realize is that anytime you console.log anything, it treats that as your return statement


[7:49] 
So to start, see what happens when you just print the input paramaters


[7:49] 
Then follow the problem


[7:49] 
it says the guess word is 4-8 characters


[7:50] 
that means you need to print something like 'AAAA'


[7:50] 
now the bulk of the logic you'll have to create, probably in some outside helper function, is going to answer this question


[7:50] 
How do i take two numbers (cows and bulls


[7:50] 
)


[7:51] 
and use those numbers to iterate on my output ('AAAA', 'BBBB' etc)


[7:51] 
so that it eventually yields 4 bulls


[7:51] 
you saw the approach I coded out quickly, which was to try random letters at a time


[7:51] 
that won't work most of the time, but it technically was a strategy


[7:52] 
you'll have to probably keep track of what your current guess is, and some associated number of bulls and cows


[7:52] 
if you can pin down a letter in its correct spot, then that's great


also remember that it iterates on its own, so you don't have to worry about recursing


[8:01] 
I guess the main thing is to play around with the function


[8:01] 
see what happens when you do different things and eventually you'll start to come up with some ideas on your own


[8:01] 
definitely feel free to reach out if you have more questions


[8:02] 
but I would recommend looking up efficient solutions online and seeing how people have solved this problem in the past


[8:03] 
because trying something like 'AAAA' will tell you definitely if an A is in the word


[8:03] 
but you won't know where


[8:03] 
and you'll have to try 26 different combinations


[8:03] 
'ABCD' will help you cover more ground


[8:04] 
But you also won't know which letter is the correct one


[8:04] 
so there are tradeoffs


[8:04] 
hope this helps!
