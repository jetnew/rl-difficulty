# RL Difficulty
Can environment difficulty predict agent performance?

## Environment Types
1. Fully vs partially observable
2. Deterministic vs stochastic
3. Competitive vs collaborative
4. Single agent vs multiple agents
5. Static vs dynamic
6. Discrete vs continuous
7. Episodic vs sequential
8. Known vs unknown

However, there exist other factors about the environment that affects task difficulty.

## Other Difficulties in RL
* Reward sparseness
* Long-term credit assignment
* State rarity
* Safety
* Presence of distractions

## Experiment Design
The maze is a well-studied environment that can be generally modified in complexity.
1. Formally define parameters of difficulty in the context of a maze, and build the corresponding gym environments.
2. Benchmark [SB3](https://github.com/araffin/rl-baselines-zoo/blob/master/benchmark.md) algorithms to varying difficulties.
3. Formulate a measure of difficulty by relating different difficulty parameters.
4. Generalize the measure of difficulty and difficulty parameters to environments in general.
5. Measure the correlation of environment difficulty to agent performance.

## Other Approaches
* Use the entropy of a predictive model as the measure of difficulty
* Use multiple environments to benchmark agent capabilities ([bsuite](https://github.com/deepmind/bsuite))
* Use the frequency and magnitude of direction change to measure difficulty of mazes ([McClendon 2001](https://archive.bridgesmathart.org/2001/bridges2001-213.pdf))