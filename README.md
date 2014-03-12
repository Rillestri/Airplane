Airplane
========

Airplane Project

//Jerry's portion Array and some basic methods

private boolean[] isTaken_FC = new boolean[4];
private boolean[] isTaken_EC = new boolean[4];
Images seatImages = new Images[2];

some pseudocode:

setInitialAvailableSeats()
int i = 0
for(i to n) //Assuming arrays start at index 0
  begin
  isTaken_FC[i] = false
  isTaken_EC[i] = false
  end
  

lblSeat(number)clicked (event)
int i = (seat number - 1)
if(istaken_FC[i] != 0)
{
  isTaken_FC[i] = false
}
  else
  {
    isTaken_FC[i] = true
  }
  
  
//Method to check seats after user has selected seats and confirmed
-Some sort of enhanced for loop
