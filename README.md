

# TextSight

**TextSight** is an Optical Character Recognition (OCR) tool that allows users to upload images and extract text in both **English** and **Hindi**. Built with **EasyOCR** for text recognition and **Gradio** for the interactive interface, the app also supports keyword search, highlighting specified keywords within the extracted text.

## Features
- Extracts text from images in English and Hindi using **EasyOCR**.
- Allows keyword search and highlights the specified keywords in the extracted text.
- Simple and interactive web-based interface built with **Gradio**.

## Live Project
You can access the live application [here](https://0eccf3fb2e63c1091e.gradio.live).

## Installation and Setup

To run **TextSight** locally or on Google Colab, follow these steps:

### Running Locally
        as
#### 1. Clone the Repository:
```bash
git clone https://github.com/Vishal5051/TextSight.git
cd TextSight
```

#### 2. Install Required Dependencies:
Install the necessary libraries by running the following command:
```bash
pip install transformers torch easyocr gradio
```

#### 3. Install Additional Requirements:
The **EasyOCR** model for **English** and **Hindi** will be automatically downloaded when you first run the application.

#### 4. Run the Python Script:
After installing all dependencies, run the main script:
```bash
python main.py
```

#### 5. Access the Application:
Once the server starts, **Gradio** will generate a local URL (e.g., `http://127.0.0.1:7860/`). Open this URL in your browser to access the **TextSight** application.

### Running on Google Colab

#### 1. Open Google Colab:
Go to [Google Colab](https://colab.research.google.com/).

#### 2. Clone the Repository:
In a new code cell, run the following commands:
```python
!git clone https://github.com/Vishal5051/TextSight.git
%cd TextSight
```

#### 3. Install Required Dependencies:
Install the necessary libraries by running the following command:
```python
!pip install transformers torch easyocr gradio
```

#### 4. Run the Application:
Run the following command to start the application:
```python
!python main.py
```

#### 5. Access the Application:
Once the server starts, **Gradio** will provide a link in the output (e.g., `https://XXXX.gradio.app`). Click this link to access the **TextSight** application.

### Usage:
1. **Upload an Image**: Upload an image containing text (supports common formats like PNG, JPEG).
2. **Keyword Search**: Enter one or more keywords, separated by commas, to highlight specific words in the extracted text.
3. The text from the image will be displayed with your keywords highlighted in **red**.

## Deployment
The application can be easily deployed on platforms like **Hugging Face Spaces** or **Streamlit Sharing**. Follow the deployment instructions specific to the platform you choose.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## About
TextSight is an Optical Character Recognition (OCR) tool that allows users to upload images and extract text in both **English** and **Hindi**. Built with **EasyOCR** for text recognition and **Gradio** for an interactive web interface, it supports keyword search to highlight specified keywords within the extracted text.

