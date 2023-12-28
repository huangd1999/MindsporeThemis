# MindsporeThemis
Themis have been deployed in the mindspore security framework, we will illustrate how to utilize it with some scripts.

## Install

```
git clone https://gitee.com/mindspore/mindarmour.git
cd mindarmour
python setup.py install
```

## Case illustration of Themis (Neuron Sensitivity Coverage)
```
cd ../examples/ai_fuzzer
python lenet5_mnist_scc.py
```

All implementation details of Themis can be seen in the:
```
https://github.com/mindspore-ai/mindarmour/blob/master/mindarmour/fuzz_testing/fuzzing.py
https://github.com/mindspore-ai/mindarmour/blob/master/mindarmour/fuzz_testing/sensitivity_convergence_coverage.py
https://github.com/mindspore-ai/mindarmour/blob/master/examples/ai_fuzzer/lenet5_mnist_scc.py
https://github.com/mindspore-ai/mindarmour/blob/master/mindarmour/fuzz_testing/scc_readme.md
```
