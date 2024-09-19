**Description:**

This project presents the implementation of an **MLP (Multilayer Perceptron) Autoencoder** using the **MNIST dataset**, which contains grayscale images of handwritten digits. The autoencoder architecture includes an **encoder** that compresses the input images to a smaller representation, and a **decoder** that reconstructs the original images. The model is trained with **60,000 images** and tested on **10,000 images**, achieving good performance in image reconstruction, noise removal, and interpolation between images.

**Key components of the project:**

- **Model Architecture**: A **4-layer autoencoder** with fully connected layers and **ReLU activations**, designed to compress and reconstruct the MNIST images.
- **Training**: The model is trained over **50 epochs** using the **Adam optimizer** with a learning rate of **1e-3**. A **scheduler** reduces the learning rate when necessary to further optimize the loss.
- **Results**: The model effectively **reconstructs input images**, removes noise from noisy images, and generates **interpolations between digit images**.
- **Applications**: Demonstrates the use of **autoencoders** in denoising and image generation tasks.

This project serves as a practical exploration of **deep learning** for **image processing tasks** using autoencoders.
