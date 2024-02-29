# In-Context Learning of Intuitive Physics in Transformers
Cristian Alamos, Masha Bondarenko, Martin Guo, Alex Nguyen, Max Vogel

## ABSTRACT

Transformers can perform new tasks when prompted with unseen test examples without updating their parameters, a phenomenon known as in-context learning (ICL). We build upon the ICL literature by investigating whether transformers can learn intuitive kinematics in context and predict the future state of a physical system given a sequence of observations. In particular, we train a transformer to predict the next position of a sequence of coordinates representing bouncing balls and vary parameters such as the strength of gravity and elasticity of the balls. We then evaluate the model’s performance on in-distribution and out-of-distribution parameter combinations and use RNNs and LSTMs as baseline comparisons. We find that transformers show significant ICL capabilities on in-distribution examples, surpassing the baseline models. Transformer models are also relatively robust to distributional shifts such as being exposed to unseen speeds in test time, but their performance degrades rapidly when Gaussian noise is injected into inputs.


***Keywords:*** Transformer · In-Context Learning

Full report [here](https://drive.google.com/drive/folders/1YvkT5Hllqc9mC_c8hPxM84K4GqRWDS95) or ./182proj_final_paper.pdf
