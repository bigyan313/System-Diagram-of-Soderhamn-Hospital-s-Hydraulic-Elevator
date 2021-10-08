# System-Diagram-of-Soderhamn-Hospital-s-Hydraulic-Elevator
System Diagram of Soderhamn Hospital's Hydraulic Elevator link: https://www.youtube.com/watch?v=tJ9Qf_UhbXY

Descriptions: Based on my assumptions:
1. Person enters through the door after using elevator control pannel outside
2. Person is allowed to used the keys to go up, go down, open door, stop and use bell
keys
3. After door is closed and user input is received, the elevator starts to move
4. After elevator achieves or passes the floor level sensor, person can stop at that
floor.
5. Person can change decisions after pressing the stop key.
6. Elevator floor position and motion is shown in the indicator lights.

PART 2
1. The Elevator Controller should control elevator to move up according to user destinations and elevator initial
position (GO UP= TRUE && REQ_FLOOR_4)is received. (For going to floor 4)
2. The Elevator Controller should control elevator to move down according to user destinations and elevator
initial position ( (GO DOWN= TRUE && REQ_FLOOR_2)is received. (For going to floor 2)
3. The Elevator Controller should control elevator to stop and reset the user inputs if (STOP= TRUE)is received
through the stop button.
4. The Elevator Controller should control elevator to open the door if (OPEN DOOR= TRUE) is received
through the open-door button.
5.The Elevator Controller should also control elevator to open the door if (OPEN DOOR= TRUE &&
CALL_FLOOR_2= TRUE)is received through the open door button from outside.
6.The Elevator Controller should control elevator to close the door if (CLOSE DOOR= TRUE) is received
through the close door button.
7.The Elevator Controller should control elevator to display arrival position according to its floor position
(Display 2 if POS_FLOOR_= 2 ) and so on.



Requriments- 
The Elevator Controller should control elevator to move up according to user destinations and
elevator initial position (GO UP = TRUE && REQ_FLOOR_4) is received. (For going to floor
4)
The Elevator Controller should control elevator to move down according to user destinations and
elevator initial position ( (GO DOWN = TRUE && REQ_FLOOR_2) is received. (For going to
floor 2)
The Elevator Controller should control elevator to stop and reset the user inputs if (STOP=
TRUE) is received through the stop button.
The Elevator Controller should control elevator to open the door if (OPEN DOOR= TRUE) is
received through the open door button.
The Elevator Controller should also control elevator to open the door if (OPEN DOOR= TRUE
&& CALL_FLOOR_2= TRUE) is received through the open door button from outside.
The Elevator Controller should control elevator to close the door if (CLOSE DOOR= TRUE) is
received through the open door button.
