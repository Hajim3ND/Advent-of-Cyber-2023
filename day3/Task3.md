Concerning today's task, the purpose was to get the password of an IT room with brute forcing using the tools crunch and hydra. To be more clear we knew that we had to get a pin password

![screenshot_1.png](https://github.com/Hajim3ND/Advent-of-Cyber-2023/blob/main/day3/images/screenshot_1.png)

and we knew that we can only imput 3 digits 

 ![screenshot_2.png](https://github.com/Hajim3ND/Advent-of-Cyber-2023/blob/main/day3/images/screenshot_2.png)

therefore the code we had to find was 3 digits-long. In order to crack the code we started by using crunch to list all the potential codes based on our current situation

 ![screenshot_3.png](https://github.com/Hajim3ND/Advent-of-Cyber-2023/blob/main/day3/images/screenshot_3.png)

then we needed to gather information about the html page,

 ![screenshot_4.png](https://github.com/Hajim3ND/Advent-of-Cyber-2023/blob/main/day3/images/screenshot_4.png) 

especially the "post", "/login.php" and "pin" informations to implement Hydra 

 ![screenshot_5.png](https://github.com/Hajim3ND/Advent-of-Cyber-2023/blob/main/day3/images/screenshot_5.png)
 
that will test every password from the list we made earlier, as soon as the tool found the code it stopped thanks to us having put the "-f" argument to avoid the tool to carry on during hours, therefore delivering
us the revelant password 

![screenshot_6.png](https://github.com/Hajim3ND/Advent-of-Cyber-2023/blob/main/day3/images/screenshot_6.png) 

that we used to get the flag after opening the door.

Screenshots mentioned can be found in the images folder of day3.

Answers :
![answers.png](https://github.com/Hajim3ND/Advent-of-Cyber-2023/blob/main/day3/images/answers.png)
