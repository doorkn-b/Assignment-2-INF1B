# First design #

- **Arnab Mukherjee**
  
# Diagram #



<u>**Accessibility description**</u> -

[The first design is a description of the thought process and the solution in words.
The two possibilites that arise are if the length of the word is either even or odd. The word if even would be averaged using the ASCII value and a new corresponding centre character will be produced. While on the other hand the length being odd, dividing it by 2 gives us a value in the form of a decimal and the floored value is taken. This gives us the position and the corresponding character is printed ](design02.jpg)

This is followed by 3 simple examples with expected result.

A very common real world use-case this design can be used for is [Encryption](https://en.wikipedia.org/wiki/Encryption), which also is an implementation of converting strings to an integer value and encoding it accordingly.

The diagram has been checked against color-blindess and partial sightedness simulators for accessibility. Above description can be transcribed to audio for a blind person for an understanding of the diagram.


# Algorithm pseudo-code #

```
define printCentreCharacter {
//define the main function


  input length = len
    
  if len is even 
       int c1 = char at len/2
       int c2 = char at (len/2)+1
       int c_avg = (c1+c2)/2
     
     
       char centre = (char) c_avg
       //convert value of c_avg to char
     print (centre)
     
  else if len is odd
       centre = floored (len/2)
       // rounded down val of result
     print (char at centre)
     
  else if len = no input
    no output
 }
     
printCentreCharacter(input)
     

```

