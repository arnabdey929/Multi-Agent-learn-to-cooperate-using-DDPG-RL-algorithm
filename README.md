# Multiple-Agents-learn-to-cooperate-using-DDPG-RL-algorithm

I trained 3 walkers who need to cooperate to carry a package without letting it fall, and without falling themselves.
The walkers are independent of each other, and have their own Value and Policy networks.
Here is an example after training for 2000 episodes
![Walkers are Walking](https://github.com/user-attachments/assets/36b5ed9f-310d-4aa0-ae0d-37e1f2b4add4)

When I used shared rewards (ie, if one of them falls all get punished), they performed very poorly.
But when I made the rewards independent they started to coordinate their movements even though initially each walker has no information of the other walkers' performances.

Lesson : For group works/projects, each individual should be uniquely rewarded instead of a shared reward fo the average group performance.
