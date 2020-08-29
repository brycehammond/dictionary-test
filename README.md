# dictionary-test
A simple iOS exercise

## The dataset

* just\_a\_dictionary.json - A sorted json array of just the words in the dictionary starting with the letter A
* dictionary.json - A json array of objects representing all the words in the dictionary

## Objective

Create an iOS application that can parse the dictionary files and do the following.  Only a final app using the full dictionary.json file is necessary.  The just\_a\_dictionary.json file is useful to prototype with.

* Show a list of the words aphabetically sorted. The sorted list should be broken into sections based on the first letter.
* Tapping on a word should show a detailed view that contains the following
    * The word in 20pt system bold font
    * The definition in 16pt system font
    * A section that contains the related words
    * A section that contains the anagrams in the dictionary of the selected word. An anagram is another word in the dictionary formed by rearranging the letters of another.  For instance, CINEMA and ICEMAN are anagrams.
    * Each word in the related/anagram sections should be selectable and go to that word's detail screen

## Testing

The sample app should include some relevant unit tests


