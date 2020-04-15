# Task 4
Robot ant was evolved with th original reward functions with seed is equal 1. For deacrease time of learning the max_step parameter was decrease in 10. 
![Image alt](https://github.com/lelami/Behavioural_robotics/raw/master/images_4_6/4_s1_original.png)

After reward functions was changed and robot ant was evolved again with seed is equal 1. 
![Image alt](https://github.com/lelami/Behavioural_robotics/raw/master/images_4_6/4_s1_modified.png)

# Task 5
Balancing bot project was succesfully created and installed.

![Image alt](https://github.com/lelami/Behavioural_robotics/raw/master/images_4_6/5_bb_folder.png)

To check the balance bot working I use the simple code.

![Image alt](https://github.com/lelami/Behavioural_robotics/raw/master/images_4_6/5_checking_code.png)

 When robot apply the reward, parameter "done" become equal "true". So, just print "It's done", when it's happening.
 
![Image alt](https://github.com/lelami/Behavioural_robotics/raw/master/images_4_6/5_work.png)

I tried to render the robot, but it didn't work because of mistake in "balancebot_env.py" file in "set_actuator" method.

# Task 6
Robot ErDiscrim was evolved 10 times with different seeds (5, 10, 15, 20, 25, 30, 35, 40, 45, 50) using LSTM architecture (parameter "architecture" in file "ErDiscrim.ini" is equal 3). 
![Image alt](https://github.com/lelami/Behavioural_robotics/raw/master/images_4_6/6_lstm.png)

After I repeat the experiment but 6 times with different seeds (5, 10, 15, 20, 25, 30) using feed-forward architecture (parameter "architecture" in file "ErDiscrim.ini" is equal 0). 
![Image alt](https://github.com/lelami/Behavioural_robotics/raw/master/images_4_6/6_feedforward.png)
