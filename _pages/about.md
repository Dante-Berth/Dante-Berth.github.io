---
permalink: /
title: "Dante-Berth's Phd"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello, I am Alexandre. My research focuses on the second-leading cause of death in advanced countries, which also poses a significant global burden. Passionate about artificial intelligence, I believe leveraging the latest AI technology can revolutionize cancer treatment. AI has the potential to offer patient-centered care by identifying optimal treatment regimes tailored to each individual. My research, titled "Reinforcement Learning for Control of Tumor Multilevel Models," aims to develop AI systems that determine the most effective treatment for each patient. 


What is Reinforcement Learning and How Reinforcement Learning can help us to treat cancers ?
======
1. Reinforcement Learning is a framework where an agent interacts with an environment and tries to maximize the expected cumulative reward. \\
$$
\max_{\pi}\sum_{t=1}^{T}\mathbb{E}_{s_{t},a_{t}	\sim \pi}[r(s_{t},a_{t})]. \\
$$
Where \\\pi\\ represents the policy, \\s_{t}\\ the state to time t, \\a_{t}\\ the action to time t and $r$ the reward.
It learns through trial and error, similar to how humans learn in video games such as Mario Bros. By attempting new tricks, you can earn more stars, more coins, and achieve a higher cumulative reward.

2. Reinforcement Learning needs an environment. In our case, it is a patient. However, we do not use real patients to train our agent; instead, we create virtual cancer micro-environments. These virtual labs serve as playgrounds for agents, allowing us to test without harming patients. In these virtual labs, we can create models centered on patient parameters to find the best treatment regime to treat their cancer.

Challenges 
======
1. Creating a virtual lab is quite complex because cancer micro-environments are highly intricate.
2. Our current virtual labs are computationally expensive, making it challenging to train an agent.
3. The data provided to our agent consists of cellular information, which is more difficult to handle than motion data.
4. Develop a robust agent capable of handling uncertainty effectively

Frameworks
======
1. [Pytorch](https://pytorch.org/)
2. [Physicell](http://physicell.org/)
