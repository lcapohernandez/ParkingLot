# ParkingLot
This is the solution to the excesrcise in 4geeks academy for the parking lot. It can also be used for other similar projects and excercises. 
We can use a 2 dimensional array (matrix) to represent the current state of a parking lot like this
let parkingState = [
  [1,0,1,1,0,1],
  [2,0,1,1,0,1],
  [1,0,2,1,0,1],
  [1,0,1,1,0,1],
  [1,0,1,1,0,2],
  [1,0,1,1,0,1],
]
📝 Instructions:
Create a function getParkingLotState() that returns an object with totalSlots, availableSlots and occupiedSlots like the following:
let state = {
     totalSlots: 12,
     availableSlots: 3,
     occupiedSlots: 9
}
💡 Hint:
You have to do a nested loop.
