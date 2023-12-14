Project Title: Analyze a Sentence

Description: 

First, this is an algorithm that can read a sentence to determine its length by considering the number of characters.
Second, the algorithm determines the word count in a sentence by considering the spaces between words (the words are separated by a single space, and stops counting the words once it encounters the fullstop). 
Third, the algorithm determines the number of vowels in a sentence. 

Example of the algorithm's use: 

Consider this sentence, "The slow grey donkey jumped over the fence." Below are the initial variables:
    sentence_length : INTEGER := 0;
    word_count : INTEGER := 0;
    vowel_count : INTEGER := 0;
    vowels : the set of characters := {'a', 'e', 'i', 'o', 'u' 'A', 'E', 'I', 'O', 'U'}
You will then iterate through the characters in the sentence. That's, after char "T", increment sentence_length by 1 and this continues until you reach the period (.), which is the last char.
For the above example, sentence_length has 43 characters. 
Iterate again looking for number of words, which are determined by single spaces between words and the fullstop; the number is 8 in our case.
Last, iterate through the characters looking for vowels, and the count will be 11 vowels in our example. 
