
Smooth Imitation Learning for Online Sequence Prediction    
Paper is [here](https://arxiv.org/abs/1606.00968)    
Code is at [here](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py)  


--

## Functions
Joint loss: [joint_loss_calculation](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L102-L110)   

Trajectory: [roll_and_smooth_learned_trajectory](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L689-L893)

--
![simile](https://cloud.githubusercontent.com/assets/12474011/18418597/c717d5b0-787b-11e6-951b-3321fab3c31c.jpg)

--
## Algorithm


input. 
[context featrue, human trajectory](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1250-L1285)
[Smooth coefficient](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1317-L1323)

1. [Initial trajectory](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1407-L1414)
2. [Initial policy](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1332-L1351)
3. [Main loop(Whole loop)](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1405-L1663)
4. [Sequentail rollout]
5. [Generate state(feature+action](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1467-L1468)
6. [Collect smooth feedback](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1479-L1483)
7. [New regularizer]
8. [Train policy](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1470-L1477)
9. [Adaptive set *beta*](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1516-L1524)
10. [Update policy](https://github.com/hoangminhle/SIMILE/blob/master/camera_simile.py#L1516-L1524)





