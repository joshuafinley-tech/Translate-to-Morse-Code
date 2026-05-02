# Translate-to-Morse-Code
I decided, I needed to know my boundaries. I struggle with computer engineering, so this means that I have to take it a bit more slowly and not jump to pygame automatically. I don't believe that computer engineering is my limit, however. I understand code a bit more than others, but that doesn't mean I know it yet. This change in pace is necessary.


(First checkpoint responses)
So I want my program to be able to effficiently take inputed text and translate it to Morse Code. I also want to program to be able to efficiiently play outloud the code. These are my current two main goals. I may also add some ease of use commands. My goal is to fulfill the criteria of mastering the while loop, making at least two functions, in some way change items in a list or a set, and maybe use three string methods.

The program is able to successfully translate text to code. The program attempts to play outloud the code, but there are some problems with the timing. I have also added two commands (/exit & /volume #), but the volume changing command needs to be fixed. My code is currently fulfilling all four of those goal criteria plus a bit of error handling for value and index errors in the volume command.

I don't know if I am adding too many comments in my program.  would also like to know if I need to make the places that I am fulfilling criteria more clear or not. 


(Second checkpoint responses)
I still want my my program to be able to effficiently take inputed text and translate it to Morse Code and be able to efficiiently play outloud the code. One of the ease-of-use commands that I may add is a /replay command and I am debating on adding a way to change the units through the terminal, but I think that will add a risk factor of changing the speed to drasticly where it will be difficult to get out of the program. I also want to add a way to end the audio while the audio is playing. 

Some of the changes that I have made to the program include making some of my notes formated more clearly. I have completely fixed the audio timing. I also added some more acceptable commands for exiting the program like "/quit" or "/stop". I could not find a way to fix the volume problems yet so I am still working on that. I will have to search online for some more solutions because apparently winsound can't control volume.  

I did use a bit of the AI chat assistance to help me look for where exacly the problem was for the audio timing and how I should go about fixing those problems, but I belive that I had asked you about if it was fine to get some assistance from the chatbot and I belive you said it was fine as long as we weren't souly just turning in ai work. which I am not. It did teach me about the enumerate function, and how it is supposed to give an index to each specified entity. I used it to seperate the imput text into words, letters, and symbols for my audio function. I hope that this is still fine with you. I don't want to add the enumerate to the translate function however because it already works correctly and I remember a saying that says "don't fix what's not broken" or somthing like that. 