This is my fairseq version
<p align="center">
  <img src="fairseq_logo.png" width="150">
  <br />
  <br />
  <a href="https://github.com/pytorch/fairseq/blob/master/LICENSE"><img alt="MIT License" src="https://img.shields.io/badge/license-MIT-blue.svg" /></a>
  <a href="https://github.com/pytorch/fairseq/releases"><img alt="Latest Release" src="https://img.shields.io/github/release/pytorch/fairseq.svg" /></a>
  <a href="https://github.com/pytorch/fairseq/actions?query=workflow:build"><img alt="Build Status" src="https://github.com/pytorch/fairseq/workflows/build/badge.svg" /></a>
  <a href="https://fairseq.readthedocs.io/en/latest/?badge=latest"><img alt="Documentation Status" src="https://readthedocs.org/projects/fairseq/badge/?version=latest" /></a>
</p>

--------------------------------------------------------------------------------

Fairseq(-py) is a sequence modeling toolkit that allows researchers and
developers to train custom models for translation, summarization, language
modeling and other text generation tasks.

## Token DROP
LDC ：47.4
fairseq：代码有bug，目标端那里shape不对，但是修复之后还不如之前，玄学
------------------------------------------------------------
fairseq_pipeline: 对抗学习流程，即优化模型、优化判别器、固定判别器和最大化判别器损失三部曲。
fairseq_reconstruct: 加入了优化P(x|x') 和 P(y|y') 的目标
fairseq_adv_recontruct: 加入了对抗的目标，最小化判别器损失
