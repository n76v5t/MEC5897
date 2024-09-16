java c
MEC5897 Lean Manufacturing 
Assignment 1 - Production Flow Analysis 
AIMS 
This assignment aims to give you a chance to practice the skills you have learned in this unit to analyse a real production system. The specific goals of this assignment are listed:
1 Be able to use Value Stream Mapping (VSM) to analyse production system
2 Be able to identify the bottleneck, calculate the utilisation of different manufacturing resources under the maximum TH conditions
3 Build a simulation model to simulate a real production process with variability
4 Be able to analyse the simulated data and compare it with the theoretical calculation learned in the class
5 Identify the waste and 3Ms and come up with potential solutions
BACKGROUND 
Fastcar is a foundry that is focusing on making an engine block for the automobile industry. Its customer is a car engine factory that assembly the engine block with other components into an engine.
Figure 1 Engine Block of a car 
In Fastcar, the Engine block is made by the die casting process withAl alloy.Figure 2 shows the manufacturing process of die casting. The melting Al liquid will be poured into the casting machine and pumped into the die. In Engine block manufacturing, the die is made of metal which can be reused, while the core is made of sand. The sand core can only be used for a single-engine block.
Figure 2 Die casting process 
The video in this link showshow to use die casting to make an engine block.
https://youtu.be/N2hYTdrzujI Fastcar received an order from its customer every two weeks. The order is sent to the marketing office of the Faster car via its online ordering system. The marketing office will upload this information on its  internal  ERP  system.  Then,  the  production  planning  office  can  be  noticed  and  contacts  the purchasing department to order  raw  materials  (Al  alloy)  and  also  prepare  the consumables. The production planning office will also inform. the workshop management team of the production plan. Workshop management will coordinate each workstation to make enough engine blocks to meet the customer orders. The engine block will be fabricated and then stored in the FG inventory. After all the units  have  been  fabricated  in the  current order. Then  Fastcar will  ship the engine  block  to  its customer by truck. Fastcar is working five days per week and 8 hours per day. 
In the workshop of Fastcar, the following process/resource should be used.
•    Step 1: Makesand core
•    Step 2: Die casting
•    Step 3: Clean and Inspection
•    Step 4: Machining
The detailed time and specifications for each resource are provided in a data file.
TASKS Task 1 (5 marks): Based on the given data collected from the production line calculate the maximum TH (Also known as process capacity). During the calculation, do not consider the machine failures and use the mean process time for calculation. Also, assume the batch size in the core making step is one. And then calculate the WIP (not include materials in the raw material inventory and FGs inventory), resource capacity, utilisation and flow time of this production line under maximum TH (no buffer inventory before each manufacturing resource is needed, also代 写MEC5897 Lean Manufacturing Assignment 1 – Production Flow AnalysisPython
代做程序编程语言 do not consider the time spend in raw material inventory and FGs inventory). Calculate resource capacity and utilisation for each step.Task 2 (5 marks): Build a simulation model to simulate the real production scenario. In this simulation model, we do not consider the variability in the process and the number of units that arrive in each order.  But you  should find the  optimal  batch  size to  maximize  the  production  TH while  keeping inventory as  low as  possible.  For  each  resource, we  use  mean  process time and  do  not consider machine breakdown. Based on the simulation model you should calculate:
1 meanTH and real TH for production line
2 Utilisation of each manufacturing resource
3 Average WIP (include raw material inventory and FGI)
4 Average Lead time for each unit, average lead time for the order (the time between order arrive and order ship to the customer)
You should draw plots to show how these values change with respect to time.
Task 3 (5 marks): Build a new model that considers the variability in your production line.   Based on this model, calculate the following items：
1 mean TH of the production line
2 real-time TH of the production line, draw a plot
3 Utilisation for each manufacturing resource.
4 Average WIP in the system (include raw material inventory and FGI)
5 Average lead time for each unit and average lead time for each order
You should draw plots to show how these values change concerning the timeTask 4 (5 Marks): Discussion on how variability from manufacturing will affect the production line. Discussion based on comparing the results from the simulation model with variability to the model without variability. (Use the simulation data to support your claim)Task 5 (5  marks): Build  VSM for this  production  process,  identify  the wastes  and  3Ms from this production line. Come up with a solution to deal with the identified waste. Build a VSM for the future state. Use the simulation model to prove that your solution is feasible (You can make reasonable assumptions. For example, move more workers to make sand core from clean and inspection can decrease 2 minin the processing time for core making and increase 2 min process time for clean and production)
DELIVERABLES
•    Deliverable 1: Assignment report (upload on moodle) . It should contain the following key points. :
o Summarize the analysis result or calculation results (Task 1, Task 2 and Task 3)
o Necessary explanation on the steps for calculation (Task 1)
o Screenshot of simulation models (Task 2, Task 3 and Task 5)
o The plot should be clear and with labels of axis and units  (all tasks)
o Necessary explanation of simulation models including how to measure the key performance parameters such as TH (Task 2, Task 3)
o The screenshot of the calculation results from the simulation model (Task 2)
o Summarize the result in a table and do a comparison    (Task 4)
o Value Stream Mapping (Task 5)
o Proposed your improvement plan and validate it with the simulation tool (Task 5)
•    Deliverable 2: simulation models (Task 2, Task 3 and Task 5). Save them separately and compress them into a zipfolder. Upload them on moodle.



         
加QQ：99515681  WX：codinghelp
