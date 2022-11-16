### *HERD*: Continuous Human-to-Robot Evolution for Learning from Human Demonstration
Created by <a href="http://xingyul.github.io">Xingyu Liu</a>, <a href="https://www.cs.cmu.edu/~dpathak" target="_blank">Deepak Pathak</a> and <a href="http://www.cs.cmu.edu/~kkitani" target="_blank">Kris Kitani</a> from Carnegie Mellon University.

### Citation

If you find our work useful in your research, please cite:

        @inproceedings{herd:liu:2022,
          title="{HERD: Continuous Human-to-Robot Evolution for Learning from Human Demonstration}",
          author={Xingyu Liu and Deepak Pathak and Kris M. Kitani},
          booktitle={The Conference on Robot Learning (CoRL)},
          year={2022},
        }

### Abstract
The ability to learn from human demonstration endows robots with the ability to automate various tasks. However, directly learning from human demonstration is challenging since the structure of the human hand can be very different from the desired robot gripper. In this work, we show that manipulation skills can be transferred from a human to a robot through the use of micro-evolutionary reinforcement learning, where a five-finger human dexterous hand robot gradually evolves into a commercial two-finger-gripper robot, while repeated interacting in a physics simulator to continuously update the policy that is first learned from human demonstration. To deal with the high dimensions of robot parameters, we propose an algorithm for multi-dimensional evolution path searching that allows joint optimization of both the robot evolution path and the policy. Through experiments on human object manipulation datasets, we show that our framework can efficiently transfer the expert human agent policy trained from human demonstrations in diverse modalities to a target commercial robot.

### Code

Code coming soon.
