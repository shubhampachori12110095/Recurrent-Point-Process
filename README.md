"Modeling The Intensity Function Of Point Process Via Recurrent Neural Networks"
############################################


Code accompanying the paper ["Modeling The Intensity Function Of Point Process Via Recurrent Neural Networks"](https://arxiv.org/abs/1705.08982)

If the code helps your research, please cite our work.

    @inproceedings{xiao2017modeling,
    title={Modeling the Intensity Function of Point Process Via Recurrent Neural Networks.},
    author={Xiao, Shuai and Yan, Junchi and Yang, Xiaokang and Zha, Hongyuan and Chu, Stephen M},
    booktitle={AAAI},
    pages={1597--1603},
    year={2017}
    }

    


## Prerequisites

- Computer with Linux or OSX
- Language: TensorFlow 1.0
- GPU is strongly recommended when training.

## Notes

- For bugs and questions, contact: benjaminforever at sjtu.edu.cn
- It would be nice if you are interested in this work and cite our paper.

## Paper Abstract:
Event sequence, asynchronously generated with random timestamp, is ubiquitous among applications. The precise and arbitrary timestamp can 
carry important clues about the underlying dynamics, and has lent the event data fundamentally different from the time-series whereby 
series is indexed with fixed and equal time interval. One expressive mathematical tool for modeling event is point process. The intensity 
functions of many point processes involve two components: the background and the effect by the history. Due to its inherent spontaneousness,
the background can be treated as a time series while the other need to handle the history events. In this paper, we model the background 
by a Recurrent Neural Network (RNN) with its units aligned with time series indexes while the history effect is modeled by another 
RNN whose units are aligned with asynchronous events to capture the long-range dynamics. The whole model with event type and timestamp 
prediction output layers can be trained end-to-end. Our approach takes an RNN perspective to point process, and models its background 
and history effect. For utility, our method allows a black-box treatment for modeling the intensity which is often a pre-defined 
parametric form in point processes. Meanwhile end-to-end training opens the venue for reusing existing rich techniques in deep network 
for point process modeling. We apply our model to the predictive maintenance problem using a log dataset by more than 1000 ATMs from
a global bank headquartered in North America.
