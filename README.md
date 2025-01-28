# RetinexWaveMamba:Retinex and Wavelet-based Lightweight Framework for Low-Light Image Enhancement with Mamba

# Introduction
Low-light image enhancement is a critical research focus in the field of image restoration. While existing enhancement methods achieve impressive results, they often involve large parameter scales and high computational complexity. Lightweight approaches can improve computational efficiency but frequently suffer from subpar enhancement performance. To address these challenges, we propose a low-light image enhancement framework that integrates spatial and frequency domains to achieve both low computational complexity and high-quality enhancement. Specifically, our method introduces a Retinex-based luminance enhancement component in the spatial domain to optimize the illumination information of images. Concurrently, multi-scale wavelet decomposition is employed to extract information from the frequency domain , facilitating the separate optimization of low-frequency and high-frequency components. For the low-frequency component, Mamba is incorporated to enhance illumination and structural restoration by leveraging global information modeling. For the high-frequency component, we utilize the similarity between low-frequency and high-frequency information to guide image restoration and enhance detail representation. By avoiding frequent alternations between spatial and frequency domains, which can lead to instability, our method fully capitalizes on the advantages of both domains. Experimental results demonstrate that the proposed framework achieves superior performance on multiple low-light image enhancement benchmarks while maintaining low computational complexity and parameter efficiency, showcasing its potential for practical applications.

# Overall Framework
![image](https://github.com/user-attachments/assets/3f88f7a2-61dc-4593-8eac-08d4363e815d)
![image](https://github.com/user-attachments/assets/d45e96f2-923e-41b2-adda-869205e658ea)

# Visuals
![image](https://github.com/user-attachments/assets/f3824859-fc45-4d1e-bc11-08a27d1230eb)
![image](https://github.com/user-attachments/assets/a637a9a6-4993-4664-8118-d15c68861d46)

