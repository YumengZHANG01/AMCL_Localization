# Localization Using AMCL 
Localize an agent in the world model using AMCL Algorithm.

- Each particle in the green cloud denotes the agent's one possible current estimated position.

- Before the prediction converges, the red agent was surrounded by a green clound(Picture 1).

- After several iterations, the prediction converges(Picture 2). We can get a relevant accurate estimated position.

### [Initial Position Estimation]<br/>
![2019-03-28-103107_1920x1056_scrot](https://user-images.githubusercontent.com/33690036/55179490-bfdbf480-5144-11e9-9efe-27a5246489a3.png)

### [Final Position Estimation]<br/>
![2019-03-28-103138_1920x1056_scrot](https://user-images.githubusercontent.com/33690036/55179496-c2d6e500-5144-11e9-8b03-430947625cfd.png)


# Partial Map Genertation Using SLAM
Since the world model is so big, only partial map is generated using SLAM. 
This map will be used for further Path Planning in that region.
![slamMap](https://user-images.githubusercontent.com/33690036/56928309-46a92780-6a8b-11e9-9dfc-2985329cb4be.jpg)
