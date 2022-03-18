## Projects

---

### [Using One Class VAEs to Analyze Bias in Deepfake Audio](https://www.youtube.com/watch?v=m44fEsZHE5w&list=PLp-0K3kfddPw0hVKPZa5JJL9fqLn_mUjO&index=24)
<img src="images/ocvaepic.png?raw=true"/>

In this project, I design and train a One-Class VAE to distinguish Real and Fake Audio from [ASVSpoof 2019](https://www.asvspoof.org/index2019.html), then analyze whether the model is biased towards a gender, to answer the question, is it easier to generate Deepfake Audio of one gender over another? [(github)](https://github.com/rkiacnhg/deepfake-audio-detection-with-ocvae) [(slides)](https://docs.google.com/presentation/d/1M14I-m-5aLAYFsq8xXGJ6vo724uJ2vNcDmUXOABGQzo/edit?usp=sharing)

---
### [Sequentializing Pytorch's Parallel Implementation of Attention for Transformers](https://github.com/rkiacnhg/sequentializing-attention-pytorch/blob/main/sequentializing_attention.ipynb)
I implemented a Sequential version of Multi-headed Attention for Transformer Models from the paper [Attention is All You Need](https://arxiv.org/pdf/1706.03762.pdf). 
The comparison shows that a parallelized implementation is preferred when there is sufficient GPU memory available, but a sequential implementation may be better when GPU usage must be conserved or limited. [(github)](https://github.com/rkiacnhg/sequentializing-attention-pytorch/)

---

## Blogpost

### [Why Gradient Clipping Methods Accelerate Training](https://medium.com/p/d3094e3290a)
I introduce a paper that theoretically explained why gradient clipping helps training on nonconvex problems.

<!-- ### [First Programming Project: 2D-Game for 1 or 2 Players :)](https://www.youtube.com/watch?v=LaxB_8od_JU&list=LL&index=39&t=7s) -->

<!-- My first programming project done in 2018. OOP based Zombie Survival game involving blaster upgrades/increasing difficulty/teammates. For 2 player, one player plays as the Zombie. [(github)](https://github.com/rkiacnhg/TP/tree/master) -->

---

## Misc

### [Conv Layer Output Size Calculator](https://rkiacnhg.github.io/convnet-calculator/)
This calculator coputes output size of Conv layers, and takes as parameters Kernel size, Channel size, Strides and Dilation. 

<p style="font-size:11px">template by <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
