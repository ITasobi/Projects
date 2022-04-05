# Projects
Just silly programs I am creating whyle learning
for Test_fyle:

For now it is working but I am still trying to:
  restrict the input to int characters
  reset the printed data for each loop
  rearrange the numbers that had been already entered into increasing order (for this I think I have to rewrite the whole thing, since it will destroy the whole conditioning afterwards. or maybe create a variable with another type of data - since the set can't be modified - and use that for printing) 

Also, sometimes i get this situation where the output of a loop is not printed until I insert another number, and then I get 2 outputs printed al at once (for the previous and the current number).
Sometimes it only prints the previous output and gives the effect of lagging behind the last input. I don't know if it's because of my code or if it's sime other external cause that won't affect the program.

 import re
    if not re.match("^[0-9]*$", guess):
        print ("Error! Only numbers allowed!")
    else:    
        guess: int = int(guess)
        
Tried this and it ruinned the loop and the program itself.
