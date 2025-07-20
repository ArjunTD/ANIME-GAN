
Anime Face Generation using GANs 🎨


A PyTorch implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) to generate 64x64 anime faces from scratch.



🚀 How to Run
Clone the repository:
git clone https://github.com/ArjunTD/ANIME-GAN.git


Install dependencies:
pip install torch torchvision opendatasets matplotlib opencv-python tqdm

Run the notebook:
Open anime-gan-project.ipynb and run all cells. The notebook will handle dataset download, training, and saving results.

🤖 Architecture
Generator: Uses transposed convolutional layers to upscale a 128-dimensional latent vector into a 64x64 color image.

Discriminator: Uses convolutional layers to downsample an image and classify it as real or fake.

🛠️ Technologies
Python, PyTorch, Jupyter Notebook, Matplotlib, OpenCV
