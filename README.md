# Lab 1.9 Chat (Part 3)

## Instructions

You are going to update the program you wrote in Lab 1.7 so that it gives a random response if it

## Starter Code

Use the code you wrote for lab 1.7 as the starter code for this lab. If you have not completed lab 1.7, then you can implement the random response using the starter code provided in this repository, however you will find it useful to complete at least part 1 of Lab 1.7 (the while loop) so that you can see multiple responses and confirm that you are getting random results.

## The Assignment

Currently, the process method will return the response "That's interesting." if it doesn't know what else to say. Update that code so that it randomly chooses between (at least) 4 choices if it has nothing else to say.

You will need to generate a random number and use if-statements to accomplish this goal. Each time the process method is invoked, it should pick a new random response.

## Testing

Run your program and enter different messages. Make sure you are getting different random responses each time you enter a message. (Getting the same response two or three times in a row is random, however getting the same response *every* time is probably not random). Also, make sure you are seeing *all* the responses to programmed. Pay close attention to whether you see the first and last responses. Often, if there is a mistake in the code you will find it with the *edge cases*, in this case when you check for the lowest and highest values of the random number.

## Grading

This lab will be manually graded by inspection.

## Turning it in

When you have finished this lab, upload it to [MrMayCS.com/turnitin](http://mrmaycs.com/turnitin)
