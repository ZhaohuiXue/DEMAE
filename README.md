# DEMAE

Running environment and required packages:
    
    python==3.8
    numpy==1.19.5
    matplotlib==3.3.4
    scipy==1.5.2
    scikit-learn==0.23.2
    opencv-python==4.5.1.48
    torch==1.10.2+cu111

Instructions for usage
---------------------
    model.py ...... A script for the implementation of DEMAE.
    model_pretraining.py ...... A script for obtaining the initial model weights through self-supervised pre-training and save the .pt file.
    main.py ...... A main script for hyperspectral image classification.
    data.py ...... A data processing script for hyperspectral image.
    loop_train_test.py ...... Perform iterative training and testing loops, saving the model weights in the 'save\models' directory, and storing the confusion matrix of the test results in the 'save\results' directory.
    loss_function.py ...... A script for calculating training loss.
    visualization.py ...... A script for drawing and visualization.

Cite:

   [1] Z. Li, Z. Xue, M. Jia, X. Nie, H. Wu, M. Zhang, H. Su. DEMAE: Diffusion-Enhanced Masked Autoencoder for Hyperspectral Image Classification With Few Labeled Samples[J]. IEEE Transactions on Geoscience and Remote Sensing, 2024, 62: 1-16.
   --------------------------------------
   Copyright & Disclaimer
   --------------------------------------

   The programs contained in this package are granted free of charge for
   research and education purposes only. 

   Copyright (c) 2021 by Zhaohui Xue & Ziyu Li
   zhaohui.xue@hhu.edu.cn
   --------------------------------------
   For full package:
   --------------------------------------
   https://sites.google.com/site/zhaohuixuers/
