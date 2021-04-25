# goto
###  The `goto` statement transfers the program control directly to a labeled statement. A common use of  `goto`  is to transfer control to a specific switch-case label or the default label in a  `switch`  statement.

The  `goto`  statement is also useful to get out of deeply nested loops.

### For example:

`switch (n) { case  1: cost += 25; break; case  2: cost += 25; goto  case  1; case  3: cost += 50; goto  case  1; default: Console.WriteLine("Invalid selection."); break; }`


  
    
 
