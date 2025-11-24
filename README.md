Neural Style Transfer

A deep learning project that blends the content of one image with the artistic style of another image using a Convolutional Neural Network.

Company: CodTech IT Solutions
Name: Mohammed Fahad Ali
Intern ID: CT04DR859
Domain: Artificial Intelligence
Duration: 4 Weeks
Mentor: Neela Santosh

Overview

This project implements Neural Style Transfer using TensorFlow and the VGG19 model. The objective is to take two images — a content image and a style image — and generate a new image that maintains the structure of the content image while applying the visual style and texture of the style image.

How It Works

A pre-trained VGG19 network is used to extract image features.

Two types of loss functions are calculated:

Content loss to preserve structure.

Style loss to apply visual textures and patterns.

The generated image is iteratively optimized until it resembles a stylized version of the content image.

Technologies Used

Python

TensorFlow / Keras

NumPy

Matplotlib

Pillow

Project Structure
Neural-Style-Transfer/
│
├── style.ipynb       
├── content.jpg        
├── style.jpg          
└── output.png        

How to Run

Clone the repository:

git clone https://github.com/your-username/Neural-Style-Transfer.git


Install dependencies:

pip install tensorflow pillow matplotlib numpy


Run the Jupyter Notebook and execute the cells.

What I Learned

How VGG19 extracts feature representations from images

Understanding and implementing content and style loss

Gradient optimization for image generation

Author

Mohammed Fahad Ali
AI/ML Intern | Generative AI Enthusiast
GitHub: Fahadaliha
LinkedIn: Mohammed Fahad Ali
