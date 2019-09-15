# DQN-Examples
Deep Q-networks demonstrated using Open-AI Gym

## Dependencies 

The code is implemented in [Python 3.6](https://www.python.org/downloads/release/python-360/) using [Keras](http://keras.io/). 
Other libraries required are [OpenAI-Gym](https://gym.openai.com/), collections and they
can be installed using [pip](https://pypi.python.org/pypi/pip).

Please refer to [this](https://github.com/openai/gym) for further information about gym environment.

## Platform

This repo uses ``` cartpole ``` and ``` mountain-car ```  environment of gym.

## How to Run this code

please run
```bash
# DQN-cartpole 
~/DQN cartpole/dqncartpole.py
```
to train a [Deep-Q network (DQN)](https://www.analyticsvidhya.com/blog/2019/04/introduction-deep-q-learning-python/) on cartpole ``` env ```

and 
```bash
# DQN mountain-car
~/DQN mountain-car/code_main.py
```
to train it on mountain car ``` env ```

## Acknowledgements
I would like to provide the following references which are great starting points to understand reinforcement learning.
* ["Asynchronous Methods for Deep Reinforcement Learning", Mnih et al., 2016](https://arxiv.org/abs/1602.01783)
* [Deep-RL Bootcamp](https://sites.google.com/view/deep-rl-bootcamp/lectures)
* [David Silver's Deep RL course](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
* [muupan's async-rl repo](https://github.com/muupan/async-rl/wiki)
* [miyosuda's async_deep_reinforce repo](https://github.com/miyosuda/async_deep_reinforce)
