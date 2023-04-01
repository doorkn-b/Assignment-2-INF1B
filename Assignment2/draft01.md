# Explaining the challenge to a beginner #

- **Arnab Mukherjee**
- **s2423463**
- **Group 05- Mon 1510-1630 (Intermediate)**
- **Brodbelt Alexander**
- **2023-02-15**


# Description #

The 'Finding the Centre' challenge requires us to find the centre of a given string of characters. These characters have an associated [ASCII](https://en.wikipedia.org/wiki/ASCII) value to them. 

Given the input is of odd length, we just return the character at the centre position. 

When the input is even we must take the average of the ASCII values of the two centres. The ASCII character of the average value must be returned which will be the centre character. Also, if the input is empty the output must also be empty.

This is what the premise of the challenge consists of.

# Original challenge question from codegolf #

[Short link to codegolf challenge](https://codegolf.stackexchange.com/questions/64599/find-the-center)

Given a string of ASCII characters, output the character that is in the middle. If there is no middle character (when the string has an even length), output the ASCII character whose ordinal is the floored average of the two center characters. If the string is empty, an empty string should be output.

<STYLE>
* {
  font-size:   1.1rem;
  /*font-size:   1.2rem;*/
  background-color: #2A252A;
  color:            #D5DAD5;
  /*background-color: DarkSlateGray;*/
  /*color:            AntiqueWhite;*/
  /*background-color: black;*/
  /*color: white;*/
  /*background-color: white;*/
  /*color: black;*/
  }
  body {
  width: 80%;
  font-family: "OpenDyslexic", serif;
  /*font-family: sans-serif;*/
  line-height: 180%;
  /*line-height: 200%;*/
  }
  pre,
  code,
  pre code {
  font-family: "OpenDyslexicMono", monospace;
  line-height: 150%;
  }
  ol,
  ol ol,
  ol ol ol {
  list-style-type: decimal;
  }  
  em {
  font-style: normal;
  border-bottom-style: solid;
  border-bottom-width: 1px;
  padding-bottom:      2px;
  /*text-decoration: underline;*/
  text-decoration-skip-ink: auto;
  }
  h2 {
  margin-top:  40px;
  padding-top: 10px;
  font-size: 1rem;
  }
</STYLE>
