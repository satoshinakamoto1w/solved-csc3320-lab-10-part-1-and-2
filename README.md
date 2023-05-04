Download Link: https://assignmentchef.com/product/solved-csc3320-lab-10-part-1-and-2
<br>
<span class="kksr-muted">Rate this product</span>

The following program splitTime.c is used to split a time in seconds into the equivalent time in hours (0-23), minutes (0-59), and seconds (0-59), respectively. But it is incomplete. Please complete the program.Sample output:

<pre>Enterseconds:2345Converted format 0 hour 39 mins 5 secs</pre>

<pre>Enter seconds:3601Converted format 1 hour 0 mins 1 secs</pre>

<pre>#include&lt;stdio.h&gt;</pre>

<pre>// Write the declaration of function split_time</pre>

int main(){

<pre>     int n,hr,min,sec;     printf("Enter seconds:");     scanf("%d",&amp;n);</pre>

/* Write the statement to call split_time */ printf(“Converted format: %d hour %d mins %d secs”, /* Write

the corresponding expressions */ ); return 0;

}*sec){

}

Purpose: Learn how to use the pointers to represent strings in C.

Part 1:

Write a function about string copy, the strcpy prototype “char* strcpy (char* strDest, const char* strSrc);”. Here strDest is destination string, strSrc is source string.

1) Write the function strcpy, don’t call C string library.2) Here strcpy can copy strSrc to strDest, but why we use char* as the return value of strcpy?

Part 2:

Write a program findStr.c that finds the “smallest” and “largest” in a series of words. After the user enters the words, the program will determine which words would come first and last if the words were listed in dictionary order. The program must stop accepting input when the user enters a four-letter word. Assume that no word is more than 20 letters long. An interactive session with the program might look like this:

<pre>Enter word: dog</pre>

<pre>Enter word: zebraEnter word: rabbitEnter word: catfishEnter word: walrusEnter word: catEnter word: fish</pre>

<pre>Smallest word: catLargest word: zebra</pre>

Hint: Use two strings named smallest_word and largest_word to keep track of the “smallest” and “largest” words entered so far. Each time the user enters a new word, use strcmp to compare it with smallest_word; if the new word is “smaller”, use strcpy to save it in smallest_word. Do a similar comparison with largest_word. Use strlen to determine when the user has entered a four-letter word.

Questions: