# PPO

To run PPO, install the dependencies for each simulator first and run the following command:

isaacgym:
```bash
python roboverse_learn/rl/train_rl.py train=CloseBoxPPO environment.sim_name=isaacgym
```

mujoco:
```bash
python roboverse_learn/rl/train_rl.py train=CloseBoxPPO environment.sim_name=mujoco
```


isaaclab:
```bash
python roboverse_learn/rl/train_rl.py train=CloseBoxPPO environment.sim_name=isaaclab
```
(note: current closebox is set for franka end effector to reach the origin point)

To change PPO configs, check out all files inside `roboverse_learn/rl/configs/`.
