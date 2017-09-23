# Java-Attempt
I was given a coding challenge to create a game, though I am very new to Java. This is a very rough work-in-progress so any advice is appreciated.  
The goal here is to produce a number guessing game. Some code will be more suited to r as I am more familiar with it.  

# Coding variables
 target1 = getRandomNumber // I am unsure how to code the getRandomNumber function, though for this our range is 0-100
 target2 = getRandomNumber  
 int Lives = 10 // The player will have 10 guesses  
 Points = 0 // This is a fairly basic scoring system, and as a result it is heavily flawed.  
 # Coding the game
 if ((getUserInput - target1) < (getUserInput - target2))  {  // Need to code absolute value for this to work  
      System.out.printin("You are closer to Target 1 than Target 2") ;  
        if (getUserInput > target1) {  
      System.out.printin("Your guess was higher");  
        else if (getUserInput < target1) {  
      System.out.printin("Your guess was lower");  
         }  
        }   
 else if ((getUserInput - target1) > (getUserInput - target2)) { // Again, absolute value is needed  
   System.out.printin("You are close to Target 2 than Target 1");  
  if (getUserInput > target2) {  
   System.out.printin("Your guess was higher");  
 else if (getUserInput < target2) {  
   System.out.printin("Your guess was lower");  
      }  
     }  
   }  
 }  
 if (getUserInput == target1 || getUserInput == target2) {  
   System.out.printin("You have correctly discovered a target number");  
    Set(Points = (Points + 1)) // unsure of how to code the points and lives mechanic.   
 else if  (getUserInput != target 1 || getUserInput != target 2) {  
   set(Lives = (Lives - 1));  
lives--; lives-=1 lives = lives - 1  
   System.out.printin("You have not correctly discovered a target number");    
   System.out.printin("You have" + Lives + "Remaining");  
   }  
 }  
 if (getUserInput == target1) {  
   System.out.printin("Target 1 was equal to" + target1);  
   }  
 if (getUserInput == target2) {  
   System.out.printin("Target 2 was equal to" + target2);  
   }  
 if (Lives == 0) {  
  System.out.printin("Game over. You have run out of lives.");  
  System.out.printin("You scored" + Points + "points");  
  System.out.printin("Target 1 was" + target1 + "and Target 2 was" + target2);  
  }  
   if (Points == 2) { // This will need to be fixed
   System.out.printin("Congratulations you have won! You had" + Lives + "lives remaining");  
   }  
   

