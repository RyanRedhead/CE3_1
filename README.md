CE3
==========
Elevator

#Moore Testbench
![Alt Text](https://github.com/RyanRedhead/CE3_1/blob/master/Mooretestbenchpicture.PNG?raw=true)
#Mealy Testbench
![Alt Text](https://github.com/RyanRedhead/CE3_1/blob/master/Mealytestbenchpicture.PNG?raw=true)
#Explanation
The outputs of Moore machines are driven by the current state while the outputs of Mealy machines are driven by the current state and the current inputs. Both of the transitions between states are driven by the rising edge of the clock. In the Moore testbench the next elevator state is dependent on the current state and is driven by the clock. In the Mealy machine the next elevator state is dependent on the current elevator state and the next floor state and is also dirven by the clock. The VHDL code is the same for both machines, and the Mealy has one more output defined, next state logic, than the Moore machine.
