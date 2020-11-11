# PigLatin

Pig Latin is a language game where words are "translated" according to the following rules:  

1.  For words that are all consonants, simply add "ay" to the end of the word. Thus, "try" becomes "tryay".  
2.  For words that begin with vowels, simply add "way" to the end of the word. Thus, "a" becomes "away"; "at" becomes "atway"; "ermine" becomes "ermineway."  
3.  For words beginning with "qu," move the "qu" to the end of the word and add ay. Thus "question" becomes "estionquay".  
4.  For words that begin with consonants, move the leading consonant(s) to the end of the word and add "ay."   
    Thus, "ball" becomes "allbay"; "button" becomes "uttonbay"; "star" becomes "arstay"; "three" becomes "eethray";  
    
For this assignment you will need to test the letters of a String one letter at a time for vowels.  
There are at least two ways to access one letter of a String, substring and charAt:  
  `ordWay.substring(0,1).equals("a")` will test if the first letter of ordWay is an 'a'  
  `ordWay.charAt(0) == 'a'` will also test if the first letter of ordWay is an 'a'  
  
  
## Suggested steps to complete this assignment  

1.  Fork the repo in Github and open it up in Repl.it  
2.  Write the code for `findFirstVowel()` to just find the first ‘a’.   
3.  Add to `findFirstVowel()` to include all vowels.  It returns the position of the first 'a', 'e', 'i', 'o' or 'u'. If the word contains no vowels (like "try"), the method should return -1.  
4.  Now, modify the `pigLatin()` method to implement all four rules of pig latin shown above. Rule 1 has already been implemented for you. When you've implemented all four rules correctly, use the following test cases to see if your PigLatin works correctly.   
5.  Your main method should prompt the user enter a word and then return the word in PigLatin.  Then ask the user if they want to enter another word (Y/ N).   
6.  You can use the following test cases to make sure your code covers all conditions.  

>central in Pig Latin is: entralcay  
>eagle in Pig Latin is: eagleway  
>beast in Pig Latin is: eastbay  
>dough in Pig Latin is: oughday  
>happy in Pig Latin is: appyhay  
>question in Pig Latin is: estionquay  
>star in Pig Latin is: arstay  
>three in Pig Latin is: eethray  
>try in Pig Latin is: tryay  

7.  Submit your code by including the link to your Repl.it file.  
