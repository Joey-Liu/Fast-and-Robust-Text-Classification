
## [Robust Text Classifier on Test-Time Budgets](https://arxiv.org/abs/1707.09457) ##
[Md Rizwan Parvez](https://sites.google.com/site/parvezmdrizwan/), [Tolga Bolukbasi](http://people.bu.edu/tolgab/) [Kai-Wei Chang](http://www.cs.ucla.edu/~kc2wc/),[Venkatesh Saligrama](https://www.bu.edu/eng/profile/venkatesh-saligrama/): EMNLP-IJCAI 2019


**For details, please refer to [this paper]()**


- ### Abstract

We design a generic framework for learning a robust text classification model that achieves high accuracy under different selection budgets  (a.k.a selection rates) at test-time. We take a different approach from existing methods and learn to dynamically filter a large fraction of unimportant words by a low-complexity selector such that any high-complexity classifier only needs to process a small fraction of text, relevant for the target task. To this end, we propose a data aggregation method for training the classifier, allowing it to achieve competitive performance on fractured sentences. On four
benchmark text classification tasks, we demonstrate that the framework gains consistent speedup with little degradation in accuracy on various selection budgets.

| ![Our framework](img/bias_teaser.png)             |
| ---------------------------------------- |
| *Structure prediction can help the model to build the correlations between different parts. However it will also cause some bias problem.* |

- ### Source Code Notes: Coming soon. 



- ### Data

- ### Reference
  Please cite

 ```
 @article{parvez2018building,
  title={Building a Robust Text Classifier on a Test-Time Budget},
  author={Parvez, Md Rizwan and Balukbasi, Tolga and Sarigrama, Venkatesh and others},
  journal={arXiv preprint arXiv:1808.08270},
  year={2018}
}
 ```
 
 

- ### Results
| ![Results](img/bias_teaser.png)             |
| ---------------------------------------- |
| *Structure prediction can help the model to build the correlations between different parts. However it will also cause some bias problem.* |

  

