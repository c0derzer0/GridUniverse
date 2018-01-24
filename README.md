# RL_problems

This repository was created with the goal of developing and reproducing many different Reinforcement Learning algorithms 
and then being able to run large scale experiments using these algorithms on different open-source 
environments as well as our own custom environments.  

Currently working exclusively on OpenAI gym and a Gridworld environment made by us.

![Alt Text](docs/maze_solver_BFS_10_times_gimp.gif)

## Examples of use

To run an example of policy and value iteration on our Gridworld environment run:  

`python examples/gridworld_examples.py`

To run tests:  

`python tests/tests.py`

## Installation

Follow the instructions at this link: [Installation instructions](https://github.com/beduffy/RL_problems/tree/master/docs/Installation.md)

## Running OpenAI gym

Now you should be able to run: 

`python examples/atari_example.py`

You should see a small window that automatically plays "Space Invaders" if everything is working correctly.

For a general documentation on how the environment works refer to the [official documentation](https://gym.openai.com/docs).

## Running GridWorld

To run our custom environment explore the code within:

`python examples/gridworld_examples.py`

The `run_random_gridworld()` function shows the simplest way to use the environment.  
For more info check the [GridWorld Documentation](https://github.com/beduffy/RL_problems/tree/master/docs/GridWorld.md)

## API Reference

You can look within the docs, examples and tests folders for more info on all aspects of this repo. 

## Contributors

Currently not looking for help from contributors. Further information to be added in the future.

## License

For information about the license of this code please refer to the corresponding file "license.txt"
