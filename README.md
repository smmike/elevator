# elevator
Java solution for the Elevator problem. 

Problem of optimal elevator movements, when it maybe requested from different floors above and below its current position. Though there could be different types of optimization, the following definition from the Wikipedia article on [Elevator algorithm](https://en.wikipedia.org/wiki/Elevator_algorithm) is used here: 
> ... the elevator continues to travel in its current direction (up or down) until empty, stopping only to let individuals off or to pick up new individuals heading in the same direction.

The following assumptions are used here:
* Passengers can request an elevator by using "Up" and "Down" buttons, so the system receives this information along with the floor ID, where this request was made.
* Passengers can request any floor that is serviced by the elevator when they enter it.
* Initial version doesn't consider load limits

The goal is to create working solution that can be easily demonstrated. A console output will be used as for demonstration purposes, to show the sequence in which passengers requests are served.
