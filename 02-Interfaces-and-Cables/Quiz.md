# QUIZ

## Question 1

### You connect two old routers together with a UTP cable, however data is not successfully sent and received between them. What could be the problem? 
- They are connected with a straight-through cable.
- They are connected with a crossover cable.
- They are operating in Auto MDI-X mode.

#### Answer: 
They are connected with a straight-through cable. 

#### Wrong Answer: 
They are connected with a crossover cable.
- A crossover cable is not the issue. A crossover cable would likely fix the issue.
- Because both routers transmit data on pins 1 and 2, a crossover cable is necessary to properly connect the transmit pins on one side of the connection to the receive pins (3 and 6) on the other side.
- Modern devices with Auto MDI-X enabled don't have this issue, but it is possible that the old routers do not have Auto MDI-X.

They are operating in Auto MDI-X mode. 
- Auto MDI-X allows devices to detect which pins and wires their neighbor is using to transmit and receive data, and adjust their own operations to match.
- Auto MDI-X would likely fix this issue, but since the routers are old they might not have the Auto MDI-X function.
