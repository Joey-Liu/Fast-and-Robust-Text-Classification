
## [Robust Text Classifier on Test-Time Budgets](https://arxiv.org/abs/1707.09457) ##
[Md Rizwan Parvez](https://sites.google.com/site/parvezmdrizwan/), [Tolga Bolukbasi](http://people.bu.edu/tolgab/) [Kai-Wei Chang](http://www.cs.ucla.edu/~kc2wc/),[Venkatesh Saligrama](https://www.bu.edu/eng/profile/venkatesh-saligrama/): EMNLP-IJCAI 2019


**For details, please refer to [this paper]()**


- ### Abstract

We design a generic framework for learning a robust text classification model that achieves high accuracy under different selection budgets  (a.k.a selection rates) at test-time. We take a different approach from existing methods and learn to dynamically filter a large fraction of unimportant words by a low-complexity selector such that any high-complexity classifier only needs to process a small fraction of text, relevant for the target task. To this end, we propose a data aggregation method for training the classifier, allowing it to achieve competitive performance on fractured sentences. On four
benchmark text classification tasks, we demonstrate that the framework gains consistent speedup with little degradation in accuracy on various selection budgets.

| ![bias](img/bias_teaser.png)             |
| ---------------------------------------- |
| *Structure prediction can help the model to build the correlations between different parts. However it will also cause some bias problem.* |

In our work, we study data and models associated with multilabel object classification (MLC) and visual semantic role labeling (vSRL). We find that (a) datasets for these tasks contain significant gender bias and (b) models trained on these datasets further amplify existing bias. For example, the activity **cooking** is over 33% more likely to involve females than males in a training set, and a trained model further amplifies the disparity to 68% at test time. We propose to inject corpus-level constraints for calibrating existing structured prediction models and design an algorithm based on Lagrangian relaxation for collective inference. Our method results in almost no performance loss for the underlying recognition task but decreases the magnitude of bias amplification by 47.5% and 40.5% for multilabel classification and visual semantic role labeling, respectively.


- ### Source Code



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
| ![bias](img/bias_teaser.png)             |
| ---------------------------------------- |
| *Structure prediction can help the model to build the correlations between different parts. However it will also cause some bias problem.* |

  

