# SuperResolution.ipynb
Implementing Super Resolution using SRCNN, ycbcr colour space and SSIM loss.
Prerequisites: Pytorch, matplotlib, numpy.
The train/test net protocol buffer definition net: "examples/SRCNN/SRCNN_net.prototxt" test_iter: 556 Carry out testing every 500 training iterations. test_interval: 500 The base learning rate, momentum and the weight decay of the network. base_lr: 0.0001 momentum: 0.9 weight_decay: 0 The learning rate policy lr_policy: "fixed" Display every 100 iterations display: 100 The maximum number of iterations max_iter: 15000000 snapshot intermediate results snapshot: 500 snapshot_prefix: "examples/SRCNN/SRCNN" solver mode: CPU or GPU solver_mode: GPU
