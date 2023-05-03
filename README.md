# NRC-Net
NRC-Net: A Robust Lightweight CRNN Framework for Detecting Valvular Cardiac diseases from Noisy Heart Sound using Optimal Feature Extraction Method

Cardiovascular diseases (CVDs) can be effectively treated when detected early, reducing mortality rates significantly. Traditionally, phonocardiogram (PCG) signals have been utilized for detecting cardiovascular disease due to their cost-effectiveness and simplicity. Nevertheless, various environmental and physiological noises frequently affect the PCG signals, compromising their essential distinctive characteristics. The prevalence of this issue in overcrowded and resource-constrained hospitals can compromise the accuracy of medical diagnoses. Therefore, this study aims to discover the optimal transformation method for detecting CVDs using noisy heart sound signals and propose a noise robust network to improve the CVDs classification performance.For the identification of the optimal transformation method for noisy heart sound data mel-frequency cepstral coefficients (MFCCs), short-time Fourier transform (STFT), constant-Q nonstationary Gabor transform (CQT) and continuous wavelet transform (CWT) has been used with VGG16. Furthermore, we propose a novel convolutional recurrent neural network (CRNN) architecture called noise robust cardio net (NRC-Net), which is a lightweight model to classify mitral regurgitation, aortic stenosis, mitral stenosis, mitral valve prolapse, and normal heart sounds using PCG signals contaminated with respiratory and random noises. An attention block is included to extract important temporal and spatial features from the noisy corrupted heart sound.The results of this study indicate that,CWT is the optimal transformation method for noisy heart sound signals. When evaluated on the GitHub heart sound dataset, CWT demonstrates an accuracy of 95.69% for VGG16, which is 1.95% better than the second-best CQT transformation technique. Moreover, our proposed NRC-Net with CWT obtained an accuracy of 97.4%, which is 1.71% higher than the VGG16.


