# Mission_coordination_project

Connect to [RDS](https://app.theconstructsim.com/#/) with your logins.

Go to "My rosjects" and run the project that you created.

## Clone the Project repository
In the same terminal, follow the instructions **ONE AFTER THE OTHER**:

```bash
cd ~/catkin_ws/src && git clone https://github.com/christolau/Mission_coordination_project_G8.git

cd ~/catkin_ws && catkin_make && source ~/catkin_ws/devel/setup.bash
```

You can now come back to the project subject.

## Make a file executable
In an other terminal, write the following instructions **ONE AFTER THE OTHER**:

```bash
cd /home/user/catkin_ws/src/Mission_coordination_project_G8/evry_project_strategy/nodes
chmod +x agent.py
chmod +x sweep.py
chmod +x round.py
cd ~
```


## How to open the simulator
To	run	the	simulation,	open	a	new	terminal	and	run	the	following	instruction:

```bash
roslaunch evry_project_description simu_robot.launch
```

### How to select the strategy you want to use
Open a new terminal and run the following instruction:

## Timing
TO run the timing strategy, copy this line in a new terminal:
```bash
roslaunch evry_project_strategy agent.launch
```
## Round
TO run the round strategy, copy this line in a new terminal:
```bash
roslaunch evry_project_strategy round.launch
```
## Sweep
TO run the sweep strategy, copy this line in a new terminal:
```bash
roslaunch evry_project_strategy sweep.launch
```

If you want to implement a new strategy, copy the files _agent.launch_ and _agent_terminal.launch_ and change in these files **type="agent.py"** into the name of your desired strategy 
