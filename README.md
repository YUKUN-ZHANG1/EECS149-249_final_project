# EECS149-249_final_project
4 person final project for berkeley eecs149/249 

## Project Goal

We will develop a small, automated sorting line-following robot. It will use a mechanical gripper to pick up objects, determine whether the object is made of iron, wood, or another material based on pressure and temperature measurements, and then transport it to the corresponding drop-off location.

The pressure sensor on the gripper will be used to confirm whether an object has been successfully grasped. A heating element on one side will maintain a temperature slightly higher than the ambient temperature; by measuring the temperature change after contact with an object, it will determine the object’s thermal conductivity, while a temperature sensor on the other side will measure the object’s initial temperature. Additionally, we will use Hall-effect sensors to detect the gripper’s position and, by combining this data with pressure readings and analyzing the relationship between the gripper’s closure and gripping force, determine whether the object is soft. The robot will use infrared sensors for black-line line-following navigation.


## References

The thermal material classification approach in this project is informed by the following research:

[1] H. Bai, H. Chen, E. Healy, C. C. Kemp, and T. Bhattacharjee, "Analyzing Material Recognition Performance of Thermal Tactile Sensing using a Large Materials Database and a Real Robot," *2022 IEEE International Conference on Robotics and Biomimetics (ROBIO)*, pp. 2255–2262, 2022. [arXiv](https://arxiv.org/abs/1711.01490).

[2] T. Bhattacharjee, J. Wade, and C. C. Kemp, "Material Recognition from Heat Transfer given Varying Initial Conditions and Short-Duration Contact," *Proceedings of Robotics: Science and Systems (RSS)*, 2015. [DOI](https://doi.org/10.15607/RSS.2015.XI.019).

[3] T. Bhattacharjee, H. M. Clever, J. Wade, and C. C. Kemp, "Material Recognition via Heat Transfer Given Ambiguous Initial Conditions," *IEEE Transactions on Haptics*, vol. 14, no. 4, pp. 885–896, 2021. [DOI](https://doi.org/10.1109/TOH.2021.3089990).
