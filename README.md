# QuantRL: Reinforcement Learning in Finance Markets
 
This is a 5-week, Winter in Data Science conducted under Analytics club and mentored by me(Sugam Kumar Thakur) and Yash Kothari.

No finance background is needed to start, You will learn everything throughout the project. We begin with Python and probability, learn RL on a simple inventory problem, and only then move to markets and quantitative finance. 
 
## Project roadmap
 
| Week | Focus |
|------|-------|
| [1](#week-1-python-basic-probability-and-git) | Python stack (NumPy, Pandas, Matplotlib), basic probability with Python, Git |
| [2](#week-2-probability-continued-and-intro-to-rl) | Probability continued (distributions, Markov chains, random walks) + intro to RL |
| 3 | Q-learning on an inventory management problem (Gymnasium environment) |
| 4 | Market-making simulator and RL agent |
| 5 | Baselines (including Avellaneda-Stoikov), evaluation, final report |

 
## Tech stack
 
Python, NumPy, Pandas, Matplotlib, Gymnasium. PyTorch is optional and only used for a stretch goal in Week 5.

---
 
## Week 1: Python, basic probability and Git
 
**Goal:** Be comfortable with NumPy, Pandas and Matplotlib, use them to simulate randomness, and be able to track your work with Git and GitHub.
 
### Topics
- Python refresher: functions, classes (needed later for environments), comprehensions
- NumPy arrays, vectorisation, `np.random`
- Pandas basics and Matplotlib plotting
- Probability by simulation: random variables, expectation, variance, law of large numbers, Monte Carlo estimation
- Git basics: `init`, `add`, `commit`, branches, `push`, pull requests
### Deliverables
- A notebook simulating dice and coin experiments and plotting the law of large numbers
- A Monte Carlo estimate of a simple quantity (for example, pi or an expected value)
### Resources
 
**Python and libraries**

- NumPy absolute beginners guide: https://numpy.org/doc/stable/user/absolute_beginners.html
- Pandas, 10 minutes to pandas: https://pandas.pydata.org/docs/user_guide/10min.html
- Matplotlib tutorials: https://matplotlib.org/stable/tutorials

**Probability**
- Harvard Stat 110 (Joe Blitzstein), lectures 1-10, on YouTube
- *Think Stats* / *Think Bayes* by Allen Downey (free online), for probability in Python
  
**Git and GitHub**
- Pro Git book (free): https://git-scm.com/book
- Learn Git Branching (interactive): https://learngitbranching.js.org
- GitHub Skills (hands-on courses): https://skills.github.com

---
 
## Week 2: Probability continued and intro to RL
 
**Goal:** Finish the probability needed for price models, then meet the core ideas of reinforcement learning.
 
### Topics
- Common distributions: Bernoulli, Binomial, Poisson, Normal
- Conditional probability, Markov chains, random walks
- Brownian motion and geometric Brownian motion (GBM), simulated in Python
- RL basics: agent, environment, reward, MDPs, policies, value functions, the Bellman equation
- Exploration vs exploitation: the multi-armed bandit with epsilon-greedy
### Deliverables
- An epsilon-greedy multi-armed bandit implemented in NumPy
### Resources
- Sutton & Barto, *Reinforcement Learning: An Introduction* (2nd ed.), Chapters 1-3 (Chapter 2 covers bandits). Free: http://incompleteideas.net/book/RLbook2020.pdf
- David Silver's RL course (DeepMind/UCL), Lectures 1-2, on YouTube
- Hugging Face Deep RL Course, Unit 1: https://huggingface.co/learn/deep-rl-course
- Stat 110 lectures on Markov chains
