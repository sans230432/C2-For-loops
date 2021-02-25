### for loops

repeat a set of statements for a __defined__ number of times

## formula

```
for LCV in range():
    #body statement
  ```

  ### loop control variable (LCV)
  an ordinary int variable that is initialized, tested, and changed as the loop executes

  ### range() function

  1 argument; range(#) --> range(stop)
  2 arguments; range(#, #) --> range(start, stop)
  3 arguments; range(#, #, #) --> range(start, stop step)

__note:__stop number is exclusive
  
  *Ex.*
  range(4) # 0, 1, 2, 3
  range(3, 8) --> 3, 4, 5, 6, 7
  range(1, 13, 3) --> 1, 4, 7, 10
