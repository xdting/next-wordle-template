Name: Ting Chen
Name: Kiran Savkar
Class Period: 10

# Wordle Design Document

### Game Engine Questions
1. How do we select the target word?
   * Create string with list of reasonable words
   * Randomly select one word from that list, set as target word, with its own string

2. How do we compare letters and words?
   * Use Contains function
   * If letters is contained in the target word, then its there
   * Then, see if it is in the correct position
   * Duplications?
      * Make new string, taking the correct-positioned letters out of target word
      * Then, every time a letter is contained, mark it down and remove it before moving on to the next letter

### Game Interface Questions
1. How do we collect input from the user?
   * keyPressed()
   * Then, create a string with whatever string, with a limit of 5 thingies inside
   * When enter, update the letters accordingly

### Game File List
1. Main driver file:
   * What will this file do
2. Other class file
