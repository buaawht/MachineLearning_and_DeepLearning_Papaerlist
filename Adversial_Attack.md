
# Adversarial Examples

A paper list of adversarial examples, not only limited to papers but also contains other resources.

## Blogs
 * [Breaking Linear Classifiers on ImageNet](http://karpathy.github.io/2015/03/30/breaking-convnets/), A. Karpathy et al.
 * [Welcome to the cleverhans blog(contains 3 fantancy blogs)](http://www.cleverhans.io/), N. Papernot & I. Goodfellow et al.
 * [Attacking Machine Learning with Adversarial Examples(OpenAI blog)](https://blog.openai.com/adversarial-example-research/), N. Papernot, I. Goodfellow, S. Huang, Y. Duan, P. Abbeel, J. Clark.
 * [Robust Adversarial Examples(OpenAI blog)](https://blog.openai.com/robust-adversarial-inputs/), Anish Athalye.
 * [Tricking Neural Networks: Create your own Adversarial Examples](https://ml.berkeley.edu/blog/2018/01/10/adversarial-examples/) 
 
## Papers
### General Principles
 * [Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199), C. Szegedy et al., arxiv 2014
 * [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572), I. Goodfellow et al., ICLR 2015

### Adversarial Attack
**BFGS**

* [Security Evaluation of Support Vector Machines in Adversarial Environments](https://arxiv.org/abs/1401.7727), Battista Biggio, Igino Corona et al., arxiv 2014
* [Evasion Attacks Against Machine Learning at Test Time](https://arxiv.org/abs/1708.06131), Battista Biggio, Igino Corona et al., arxiv 2017
* [Intriguing properties of neural networks](https://arxiv.org/abs/1312.6199), C. Szegedy et al., arxiv 2014

**FGSM**

* [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572), I. Goodfellow et al., ICLR 2015

**BIM**

* [Adversarial Examples In The Physical World](https://arxiv.org/pdf/1607.02533v3.pdf), A. Kurakin et al., ICLR workshop 2017 

**JSMA**

* [The Limitations of Deep Learning in Adversarial Settings](https://arxiv.org/abs/1511.07528), N. Papernot et al., ESSP 2016

**DeepFool**

* [DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599), S. Moosavi-Dezfooli et al., CVPR 2016

**CW(The Carlini and Wagner)**

* [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644), Nicholas Carlini, David Wagner., arxiv 2017

**Papernot Method**

* [Adversarial perturbations against deep neural networks for malware classification](https://arxiv.org/abs/1606.04435), Kathrin Grosse, Nicolas Papernot et al., arxiv 2016

**Universal Perturbations**

* [Universal adversarial perturbations](https://arxiv.org/abs/1610.08401), Seyed-Mohsen Moosavi-Dezfooli, Alhussein Fawzi et al., CVPR 2017
* [Analysis of universal adversarial perturbations](https://arxiv.org/abs/1705.09554), Seyed-Mohsen Moosavi-Dezfooli, Alhussein Fawzi et al., arxiv 2017

**Transferability and Black-Box Attacks**

* [Transferability in Machine Learning: from Phenomena to Black-Box Attacks using Adversarial Samples](https://arxiv.org/abs/1605.07277), N. Papernot et al., arxiv 2016
* [Delving into Transferable Adversarial Examples and Black-box Attacks](https://arxiv.org/abs/1611.02770) Liu et al., ICLR 2017
* [Practical Black-Box Attacks against Deep Learning Systems using Adversarial Examples](https://arxiv.org/abs/1602.02697), N. Papernot et al., Asia CCS 2017

**Obfuscated Gradients**

* [Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples](https://github.com/anishathalye/obfuscated-gradients), Anish Athalye and Nicholas Carlini and David Wagner, arxiv, 2018

### Defence
**Adversarial Training**

* [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572), I. Goodfellow et al., ICLR 2015
* [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083), Aleksander Madry, Aleksandar Makelov et al., arxiv 2017
* [Adversarial Machine Learning At Scale](https://arxiv.org/pdf/1611.01236.pdf), A. Kurakin et al., ICLR 2017
* [Ensemble Adversarial Training: Attacks and Defenses](https://arxiv.org/abs/1705.07204), Florian Tramèr, Alexey Kurakin, Nicolas Papernot, Ian Goodfellow, Dan Boneh, Patrick McDaniel, ICLR 2018

**Defensive Distillation**

* [Distillation as a Defense to Adversarial Perturbations against Deep Neural Networks](https://arxiv.org/pdf/1511.04508.pdf), N. Papernot et al., SSP 2016
* [Extending Defensive Distillation](https://arxiv.org/abs/1705.05264), N. Papernot et al., arxiv 2017

**Feature Squeezing**

* [Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks](https://arxiv.org/abs/1704.01155), Weilin Xu, David Evans, Yanjun Qi, arxiv 2017
* [Feature Squeezing Mitigates and Detects Carlini/Wagner Adversarial Examples](https://arxiv.org/abs/1705.10686), Weilin Xu, David Evans, Yanjun Qi, arxiv 2017

**Detection systems**

* [On the (Statistical) Detection of Adversarial Examples](https://arxiv.org/abs/1702.06280), Kathrin Grosse, Praveen Manoharan, Nicolas Papernot, Michael Backes, Patrick McDaniel, arxiv 2017
* [On Detecting Adversarial Perturbations](https://arxiv.org/abs/1702.04267), Jan Hendrik Metzen, Tim Genewein, Volker Fischer, Bastian Bischoff, arxiv 2017
* [Detecting Adversarial Samples from Artifacts](https://arxiv.org/abs/1703.00410), Reuben Feinman, Ryan R. Curtin, Saurabh Shintre, Andrew B. Gardner, arxiv 2017
 
### Others
* [Deep Neural Networks are Easily Fooled: High Confidence Predictions for Unrecognizable Images](https://arxiv.org/abs/1412.1897), A. Nguyen et al., CVPR 2015
* [Distributional Smoothing with Virtual Adversarial Training](https://arxiv.org/abs/1507.00677), T. Miyato et al., ICLR 2016
* [Adversarial Training Methods for Semi-Supervised Text Classification](https://arxiv.org/abs/1605.07725), T. Miyato et al., ICLR 2017
 
### Domains

**Image Classify**

* [Adversarial examples in the physical world](https://arxiv.org/abs/1607.02533), Alexey Kurakin, Ian Goodfellow, Samy Bengio, arxiv 2017 

**Face Recognition**

* [Accessorize to a Crime: Real and Stealthy Attacks on State-of-the-Art Face Recognition](https://www.cs.cmu.edu/~sbhagava/papers/face-rec-ccs16.pdf), Mahmood Sharif, Sruti Bhagavatula, Lujo Bauer

**Autonomous Driving**

* [Robust Physical-World Attacks on Deep Learning Models](https://arxiv.org/abs/1707.08945), Ivan Evtimov, Kevin Eykholt, Earlence Fernandes et al., arxiv 2017
* [Concrete Problems for Autonomous Vehicle Safety:Advantages of Bayesian Deep Learning](http://mlg.eng.cam.ac.uk/rowan/files/ijcai2017.pdf), Rowan McAllister et al.

 **Reinforcement Learning**

* [Adversarial attacks on neural network policies](https://arxiv.org/abs/1702.02284), S. Huang et al, ICLR workshop 2017
* [Tactics of Adversarial Attacks on Deep Reinforcement Learning Agents](https://arxiv.org/abs/1703.06748), Y. Lin et al, IJCAI 2017
* [Delving into adversarial attacks on deep policies](https://arxiv.org/abs/1705.06452), J. Kos et al., ICLR workshop 2017

**Segmentation & Object Detection**

* [Adversarial Examples for Semantic Segmentation and Object Detection](https://arxiv.org/pdf/1703.08603.pdf), C. Xie, ICCV 2017
 
## Talks&Slides
* [Do Statistical Models Understand the World?](https://www.youtube.com/watch?v=Pq4A2mPCB0Y), I. Goodfellow, 2015
* [Classifiers under Attack](https://www.usenix.org/conference/enigma2017/conference-program/presentation/evans), David Evans, 2017
* [Adversarial Examples in Machine Learning](https://www.usenix.org/conference/enigma2017/conference-program/presentation/papernot), Nicolas Papernot, 2017
* [Adversarial Examples and Adversarial Training](https://www.youtube.com/watch?v=CIfsB_EYsVI&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv), I. Goodfellow, 2017 [[slide]](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture16.pdf)

## Repositories and tools
* [Cleverhans](https://github.com/tensorflow/cleverhans): a great TensorFlow-based library for adversarial attacks and defences.
* [FoolBox](https://foolbox.readthedocs.io/en/latest/): another collection of attacks that you can use with a framework of your preference.

## Competitions
* [Non-targeted attacks](https://www.kaggle.com/c/nips-2017-non-targeted-adversarial-attack)
* [Targeted attacks](https://www.kaggle.com/c/nips-2017-targeted-adversarial-attack)
* [Defences](https://www.kaggle.com/c/nips-2017-defense-against-adversarial-attack)

----
## References
* https://www.zybuluo.com/wuxin1994/note/888889
* https://blog.xix.ai/how-adversarial-attacks-work-87495b81da2d
* https://github.com/yenchenlin/awesome-adversarial-machine-learning


