Proposed Methodology:
- The methodology uses a deep encoder-decoder network designed to improve source separation in the time domain.
- Includes experimentation with dilated convolutional layers to extend temporal context.
![image](https://github.com/user-attachments/assets/bc813f63-50c6-42d2-b9df-321bca39db0d)

Encoder-Decoder Module Architecture:
- The encoder consists of four nonlinear layers (G=4), and the first layer applies linear transformations via 1D convolution.
- A dilated version of the encoder-decoder was also tested with exponentially increasing dilation factors, enhancing temporal context.
![image](https://github.com/user-attachments/assets/f3c884b2-b898-4392-8b83-cf6569324cbe)
