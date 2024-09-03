# underwater-image-enhancement
## Abstract
Underwater imaging poses significant challenges due to the absorption and scattering of light in water, which leads to several issues:

    Absorption of Light: Water absorbs light, and this absorption varies with wavelength. As depth increases, longer wavelengths such as red, orange, and yellow are absorbed more quickly than shorter wavelengths like blue and green. This results in underwater images that are predominantly bluish-green, lacking in red tones, which can cause color distortion.

    Scattering of Light: Particles in water, such as suspended sediments and plankton, scatter light. This scattering reduces image contrast and sharpness, making objects appear hazy or blurry, and limiting visibility.

    Low Contrast: Due to absorption and scattering, underwater images often have low contrast, making it difficult to distinguish between different objects or features.

    Color Distortion: The selective absorption of different wavelengths results in color distortion, making objects appear a different color than they would in air or at shallow depths.

    Reduced Visibility: All these factors combined reduce visibility, which is a major issue for applications like underwater inspection, navigation, and surveillance.

To counter these issues, various image enhancement techniques are employed:

    Histogram Equalization: This technique is used to improve contrast by redistributing the intensity values of the image, making details more visible.

    Color Correction: Algorithms can be used to adjust the color balance in underwater images, compensating for the loss of red and other longer wavelengths.

    Dehazing: Techniques like dehazing are used to reduce the effect of scattering, improving the clarity and sharpness of underwater images.

    Image Restoration: This involves more sophisticated approaches, such as using models of light propagation and machine learning algorithms, to reconstruct a more accurate representation of the scene.

These enhancement techniques are crucial for making underwater images useful for various applications, such as marine biology research, underwater archaeology, inspection of underwater structures, and navigation.

## Block Diagram 
![block_diagram](https://github.com/sunnypriyadarshi81/Underwater-Image-Enhancement-using-Fusion/blob/main/images/block_diagram.png)

This diagram illustrates an image enhancement process starting with color correction using the compensation of color channels and the Gray World Algorithm, followed by contrast enhancement through global histogram equalization and unsharp masking. The enhanced outputs are fused and finalized using either averaging-based or PCA-based fusion methods to produce an enhanced image.

## Results
![block_diagram](https://github.com/sunnypriyadarshi81/Underwater-Image-Enhancement-using-Fusion/blob/main/images/result1.PNG)
![block_diagram](https://github.com/sunnypriyadarshi81/Underwater-Image-Enhancement-using-Fusion/blob/main/images/result2.PNG)





