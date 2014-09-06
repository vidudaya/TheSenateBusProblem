==================================================================================================
				CS4532 Concurrent Programming
                       Take Home Lab 4 
             @authors Bandara H.M.V.N. (100055X) and Bashani J.P.S.(100059M)

==================================================================================================

class "BusProblem" contains the main method. 

If you are using the command prompt :
1) compile it using : javac BusProblem.java
2) run it using : java BusProblem
		- give the input parameter (rider count)
		
NOTE : the program is implemented to stop after all riders boarded to the bus. If you don't want that to happen just disable that by removing 

countNumberOfRidersWent-=n;  in line 69

line 87,88,89
// block 'check'
            if(countNumberOfRidersWent==0){
                break;
            }		
			
==================================================================================================