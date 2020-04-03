# Waymo: Automated Data Augmentation
#### Building a new augmentation strategy for lidar point clouds

"Each augmentation operation is associated with a probability and specific parameters. For example, the GroundTruthAugmentor has parameters denoting the probability for sampling vehicles, pedestrians, cyclists, whereas the GlobalTranslateNoise operation has parameters for the distortion magnitude of translation operation on x, y and z coordinates.

To automate the process of finding good augmentation policies for lidar point clouds, we created a new automated data augmentation algorithm - Progressive Population Based Augmentation (PPBA). PPBA builds on our previous Population Based Training (PBT) work, where we train neural nets with evolutionary computation, which uses principles similar to Darwin’s Natural Selection Theory. PPBA learns to optimize augmentation strategies effectively and efficiently by narrowing down the search space at each population iteration and adopting the best parameters discovered in past iterations."

Source: [Waymo](https://blog.waymo.com/2020/04/using-automated-data-augmentation-to.html)

[<p align="center"><img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/waymo.gif" width="600"></p>](https://blog.waymo.com/2020/04/using-automated-data-augmentation-to.html)


# ACM Prize in Computing Awarded to AlphaGo Lead David Silver

David Silver was announced to win the 2019 ACM Prize in Computing for breakthrough advances in computer game-playing using deep reinforcement learning. Silver is a Professor at University College London and a Principal Research Scientist at DeepMind. His most highly publicized achievement was leading the team that developed AlphaGo, that defeated the world champion in the game Go. Silver developed AlphaGo aby combining ideas from deep learning, reinforcement learning, traditional tree-search and large-scale computing. AlphaGo is recognized as a milestone in AI research and was ranked by New Scientist magazine as one of the top 10 discoveries of the last decade.

- From: [source](https://awards.acm.org/about/2019-acm-prize)
- Read more about [AlphaGo](https://deepmind.com/research/case-studies/alphago-the-story-so-far)

<p float="left">
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/silver.png" width="200" />
  <img src="https://github.com/Machine-Learning-Tokyo/AI-ML-Newsletter/blob/master/images/alphago.png" width="600" /> 
</p>
