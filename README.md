# linux-documentation


1. cal :-  use to see calander 
2. history
3. !no. :- for example: !2 
           this will run index no. 2 command of history command list 
4. !!  :-  this runs list command listed in history command

5. which (command)  :- for example: which ls
                       this will show ls commands code is in which location



6. tty :- The primary output is the path to the terminal device file
7. cut :- cut -b 1-7 example.txt  :- cuts from byte
          cut -c 1-7 example.txt  :- cuts from character
          cut -d " " -f 1 example.txt  :- cuts from the field
        
   -b (bytes): Counts and extracts based on the actual byte size of each character, which can differ for multi-byte characters like those found in UTF-8.
   -c (characters): Counts and extracts based on the number of characters, considering each character as a unit, regardless of its byte size.
