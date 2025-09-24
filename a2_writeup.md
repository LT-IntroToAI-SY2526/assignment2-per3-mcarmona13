# Assignment 2 - Write UP

## Description
This assignment is about learning and applying the while loop and iterating through multiple lists at a time.  We also will discuss how we match things in chatbots in order to extract what a user is trying to find.  Next assignment we will work with data bases and how we can extract information from them.

## What to complete
1. Go through the notes.py file w/ Mr. Berg
2. Complete `a2.py`, Mr. Berg will walk everyone through the process
3. Make sure you pass all asserts in `a2.py`
4. Complete the reflection problems below
5. Push your code to github for grading

## Reflection Questions
1. What was difficult for you while completing the match function?
The hardest part for me was figuring out how to make the % work. Its supposed to match any number of words, including none, so I had to think hard about how to loop through the source list without messing things up. I also got stuck a bit when % was at the end of the pattern, because I had to make sure it grabbed everything that was left in the source. Debugging took a wile becuase sometimes the code would almost work but not pass all the tests.


2. Explain how you could use the match function for extracting information from a movie database.
You could use the match function to figure out what someone is asking for in a sentence. For example, if someone says "show me action movies from 2010,", you could use a pattern like ["show", "me", "_", "movies", "from", "_"] and it would grab "action" & "2010". Then you could use that info to search the movie database and give them what they're looking for. This would help pick out the important words from a sentence.   

