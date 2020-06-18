This is my fairseq version
# Token DROP

- fairseq：代码有bug，目标端那里shape不对，但是修复之后还不如之前，玄学，这个在ldc上尤其好用
- fairseq_pipeline: 对抗学习流程，即优化模型、优化判别器、固定判别器和最大化判别器损失三部曲。
- fairseq_reconstruct: 加入了优化P(x|x') 和 P(y|y') 的目标
- fairseq_adv_recontruct: 加入了对抗的目标，最小化判别器损失
