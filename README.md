# Image-encryption-and-decryption-using-Rubiks-cube-algorithm
In this repo I will put my final project for the image processing course
This is a image encryption/decryption algorithm based on Runik's cube principle [based on this paper](https://www.hindawi.com/journals/jece/2012/173931/)
## REQUIREMENTS :
  - python 3
  - cv2 module
  - matplotlib.pyplot
  - matplotlib.image
  - numpy
## Algorithm Review:
### Introduction:
The Rubik's Cube Image Encryption/Decryption algorithm presented here leverages the principles of Rubik's cube to secure digital images. It is designed to provide a simple yet effective method for encrypting and decrypting grayscale images, ensuring confidentiality and privacy. The algorithm combines bitwise operations, randomization, and circular shifts to create a robust encryption scheme.

### Key Features:
#### 1. Grayscale Image Processing:
The algorithm begins by converting the original image to grayscale, simplifying the subsequent encryption process. This grayscale transformation maintains the essential details of the image while reducing complexity.

#### 2. Randomization with Alpha and Beta Values
Randomization plays a crucial role in the encryption process. The algorithm generates random vectors vector_Kr and vector_Kc for row and column shifts, respectively. The use of these vectors, combined with circular shifts, enhances the unpredictability of the encryption.

#### 3. XOR Operations for Enhanced Security
The algorithm employs XOR operations during both encryption and decryption processes. This bitwise operation enhances the security of the algorithm, introducing complexity to the pixel manipulation and providing a strong foundation for secure image transmission.

#### 4. Row and Column Sum Calculation
The algorithm calculates row and column sums during both encryption and decryption. These sums, represented by Alpha_array and Beta_array, play a vital role in the circular shifting process. Modulo 2 operations are applied to obtain binary values, ensuring data integrity.

#### 5. Visualization and Analysis
The algorithm includes visualizations of the original, grayscale, encrypted, and decrypted images, allowing users to observe the impact of encryption on the visual content. Additionally, histograms are plotted to analyze pixel value distributions before and after encryption.

### Usage Guidelines:
Image Encryption: To encrypt an image, the user needs to set the hyperparameter alpha and run the encryption process. The encrypted image can be visualized and analyzed using the provided histogram.

### Image Decryption:
Decryption is achieved by applying the inverse operations in a systematic manner. The algorithm reverses the circular shifts and XOR operations to restore the original grayscale image.

### Conclusion:
The Rubik's Cube Image Encryption/Decryption algorithm provides a novel approach to securing digital images. By integrating principles inspired by the Rubik's cube, the algorithm introduces a layer of complexity that enhances the security of image data. Users can leverage this algorithm for secure image transmission and storage, with the provided visualizations aiding in the analysis of encryption effects.

## Usage Example:
Original image:




