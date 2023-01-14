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
In the same terminal, write the following instructions **ONE AFTER THE OTHER**:

```bash
$cd /home/user/catkin_ws/src/Mission_coordination_project_G8/evry_project_strategy/nodes
$chmod +x agent.py
$chmod +x strategy2.py
$chmod +x roundabout.py
$cd ~
```
