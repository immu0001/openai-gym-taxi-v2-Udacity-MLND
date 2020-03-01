# openai-gym-taxi-v2-Udacity-MLND
udacity machine learning nano degree mini project in openai gym taxi environment
# Machine Learning Engineer Nanodegree
# Reinforcement Learning
## Project: OpenAI Taxi V2
.......
## Install

This project requires **Python 3.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [gym](https://gym.openai.com/)
- [sys](https://docs.python.org/3/library/sys.html)
- [math](https://docs.python.org/3/library/math.html)
- [deque](https://docs.python.org/2/library/collections.html)


For this coding exercise, you will use OpenAI Gym's Taxi-v2 environment to design an algorithm to teach a taxi agent to navigate a small gridworld. The goal is to adapt all that you've learned in the previous lessons to solve a new environment!

Before proceeding, read the description of the environment in subsection 3.1 of [this paper](https://arxiv.org/pdf/cs/9905014.pdf).

You can verify that the description in the paper matches the OpenAI Gym environment by peeking at the code [here](https://github.com/openai/gym/blob/master/gym/envs/toy_text/taxi.py).

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
python main.py
```  

This will run the file main.py, which finds the best reward average in a 100 episodes window.

### Evaluate your Performance

OpenAI Gym defines "solving" this task as getting average return of 9.7 over 100 consecutive trials.

While this coding exercise is ungraded, we recommend that you try to attain an average return of at least 9.1 over 100 consecutive trials (best_avg_reward > 9.1).
