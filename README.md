
# **A Novel Approach for Adaptive Detection of Small and Low Contrast Coalesced Objects**

This repository implements an adaptive detection approach for small and low contrast coalesced objects. The code is currently pending upload, awaiting acceptance of the associated paper.




# **A Step-wise Literature and Algorithm Evaluations**

The repository provides a step-wise journey that outlines the course of actions taken to achieve the final goals of the project. Each step includes an implementation and results, which can be accessed through the provided Colab notebook [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/imadalishah/SNUFS/blob/main/SNUFS_Journey.ipynb)




# **Step-1: CDC comparison based on Sobel, Scharr, Schmid and LoG Operators**

This step involves a comparison of the CDC algorithm using Sobel and Scharr Operators, which are two different convolution operators commonly used for image processing tasks.

![image](https://user-images.githubusercontent.com/57298558/231416897-2f4713b1-6831-4617-add1-f912464fb3fd.png)
<img width="760" alt="image" src="https://user-images.githubusercontent.com/57298558/231909586-03708265-b389-4bef-ac51-0a8cb66d0311.png">




# **Step-2: fast Fourier Convolution (FFC) and its evaluation based on Sobel, Scharr, Schmid and LoG Operators**

In this step, the FFC algorithm is implemented and evaluated based on Sobel and Scharr Operators. The FFC algorithm is known for its fast computation of convolutions using Fourier transform.

![image](https://user-images.githubusercontent.com/57298558/231417077-dedddda5-31d2-447f-bc56-c41bfdc670f2.png)
<img width="758" alt="image" src="https://user-images.githubusercontent.com/57298558/231909634-2f2a31c9-2d3a-4520-b252-7eec11761d26.png">




# **Step-3: CDC followed by FFC based on Sobel, Scharr, Schmid and LoG Operators**

This step combines the CDC and FFC algorithms, where the CDC is applied first followed by FFC, and the evaluation is performed based on Sobel and Scharr Operators.

![image](https://user-images.githubusercontent.com/57298558/231417209-ad7d9140-5b25-4333-8b8a-6a4bbf28778f.png)
<img width="755" alt="image" src="https://user-images.githubusercontent.com/57298558/231909680-f1449963-0469-454b-9c1a-017e088fc89f.png">




# **Step-4: Parallel CDC and FFC with Concatenation Operation**

In this step, the CDC and FFC algorithms are applied in parallel, and the results are concatenated using a concatenation operation. This step aims to further optimize the detection approach.

![image](https://user-images.githubusercontent.com/57298558/231417365-0989a390-5049-4f34-b3b2-b7f09269ef4c.png)
<img width="763" alt="image" src="https://user-images.githubusercontent.com/57298558/231909720-aa00c200-5bb0-413c-87cd-6961d024fb19.png">




**Step-5: Self-Attention Mechanism Based Object Enhancement**

Self-attention mechanisms, such as the Self-Attention Generative Adversarial Networks (SAGAN) or the Non-Local Neural Networks (NLNN), can also be used for image enhancement as an alternative to FFT-based convolution. In thi step Self-Attention mechanisms is used for image enhancement

![image](https://user-images.githubusercontent.com/57298558/231591893-3ba65779-b784-4f2f-99f4-47d5b69bd1fe.png)
<img width="694" alt="image" src="https://user-images.githubusercontent.com/57298558/231909767-174781e1-7313-4e95-8c57-21477a9e70a1.png">



Note: Detailed implementation and results for each step can be found in the associated Colab notebook, which can be accessed through the repository.




# **Contact**

[![LinkedIn](https://user-images.githubusercontent.com/57298558/231293935-ead7992d-43a1-4de7-a023-3800fdecd331.png)](https://www.linkedin.com/in/imadalishah)
[![Twitter](https://user-images.githubusercontent.com/57298558/231293638-7be4782a-6851-4049-969e-0bd0ce067276.png)](https://www.twitter.com/imadalishah)
[![Github](https://user-images.githubusercontent.com/57298558/231293745-ae272207-5087-4ea6-a3ee-184fccc8a492.png)](https://www.github.com/imadalishah)
