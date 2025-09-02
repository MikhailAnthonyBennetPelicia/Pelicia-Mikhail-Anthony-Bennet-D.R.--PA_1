# Pelicia-Mikhail-Anthony-Bennet-D.R.--PA_1
### This is my submission for the first programming assignment for Introduction to Python

## The first section of this code is called "Alphabet Soup"
#### The instruction was to create a function which takes a string and sorts the letters in the string and returns the letters in alphabetical order. To do this, I first defined the function "alphabet_soup(word)". I then used the function sorted, which sorts the characters of the string into sorted list in alphabetical order. And finally, I used to function "''.join" to combine the sorted list back into a string. And it returns the alphabetically sorted string.
#### Here's a section of the code that was used:
def alphabet_soup(word):
    return ''.join(sorted(word)) 
print(alphabet_soup("pelicia"))
aceiilp

## The second section of this code is called "Emoticon Problem"
#### The goal for this one was to create a function which changes specific words into emoticons (:), :D, :(, >:() when given a sentence. In order to do this, I first defined the function "emotify(emotion)" which uses the function ".replace()" which assigns the emoticon to the corresponding word it has to replace. Then with the return function, it shows the modified output.
#### Here's a section of the code that was used:
def emotify(emotion):
    emotion = emotion.replace('smile', ':)')
    emotion = emotion.replace('grin', ':D')
    emotion = emotion.replace('sad', ':(')
    emotion = emotion.replace('mad', '>:(')
    return emotion
print(emotify("No classes make me smile."))
No classes make me :).

## The third section of this code is called "Unpacking List Problem"
#### The objective of this section was to create a code that would unpack a list into three variables (first, middle, last) and then print all the elements. I first created the list "writeyourcodehere" which contains "[1,2,3,4,5,6]". Then I assigned the elements using the index. First = [0] which is the first index, Middle = [1:-1] which is takes the indexes starting from the second one and the one before the last index, and Last = [-1] which is the last index. And using the print function extracts the sections of the list.
#### Here's a section of the code that was used:
print("Unpacked List: ")

writeyourcodehere = [1,2,3,4,5,6]

first = writeyourcodehere[0]
middle = writeyourcodehere[1:-1]
last = writeyourcodehere[-1]
Unpacked List: 
print("First = ", first)
First =  1
