
# COMP-545 project

# GPT-3

To fit BNSLs to GPT-3 scaling behaviors, open fit__gpt_3__bnsl_jax.ipynb and run all the cells in order; e.g. open in a google colab and click "Runtime > Run all".

# BIG-Bench

To fit BNSLs to BIG-bench scaling behaviors, open fit__big_bench__bnsl_jax.ipynb and run all the cells in order; e.g. open in a google colab and click "Runtime > Run all".

# 4 Digit Addition

To fit BNSLs to 4 digit addition scaling behaviors as number of seeds vary, open fit__4_digit_addition__bnsl_jax.ipynb and run all the cells in order; e.g. open in a google colab and click "Runtime > Run all".

To obtain more training runs of N-digit addition scaling behavior, run the adder.py while in the minGPT directory. For example, to obtain a training run at training dataset size of 640 when the random seed of the training run is 1, run this command while in the minGPT directory:

python adder.py --training_dataset_size=640 --training_batch_size=640 --seed=1

The code is minGPT directory is a fork of https://github.com/karpathy/minGPT
