🧠 Neural Network Optimization: Regularization and Dropout

Overview

This project focuses on optimizing deep neural networks through custom regularization techniques and dropout, implemented directly in PyTorch. It combines theoretical derivations, mathematical gradient formulations, and practical experiments to explore how optimization strategies affect generalization and performance.

The project completes and tests dropout layers, L2 regularization penalties, and manual weight updates (bypassing built-in optimizers) to gain a deep, hands-on understanding of neural network learning dynamics.


🚀 Features

✅ Derived and implemented a modified cost function penalizing weights near ±1

✅ Analyzed deep gradient behavior and its implications for trainability in deep chains

✅ Completed a custom Dropout layer class in PyTorch with proper scaling

✅ Implemented L2 regularization (Frobenius norm penalty) in the RobustNetwork class

✅ Trained networks on test datasets, comparing regularized vs. unregularized performance

✅ Investigated the effects of dropout and regularization on reducing test error

⚙️ Tech Stack
* Python 3
* PyTorch (manual weight updates, no built-in optimizers)
* NumPy
* Jupyter Notebooks (a3q2b.ipynb, a3q3.ipynb)
* Google Colab (for GPU-based training and experimentation)

📊 Key Results
* Demonstrated how deep networks face shrinking gradient intervals as weight magnitudes increase, impacting trainability
* Successfully implemented dropout, verifying proper neuron deactivation and scaling during training
* Achieved lower test error when applying dropout and L2 regularization compared to baseline models
* Visualized the interval widths and error curves, providing insight into optimization dynamics