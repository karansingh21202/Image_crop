
# Image_crop

Image_crop is a small application that utilizes OpenCV to detect the edges of a paper in an image and crop it. The purpose of this project is to automate the document scanning process by identifying the paper boundaries and producing a cropped image.

## Features

- Edge detection using OpenCV.
- Contour detection for isolating paper edges.
- Perspective transformation to rectify paper orientation.
- Cropping the image to retain only the paper area.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV library (`pip install opencv-python`)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/karansingh21202/Image_crop.git
cd Image_crop
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

### Usage

1. Run the script:

```bash
python image_crop.py path/to/your/image.jpg
```

Replace `path/to/your/image.jpg` with the path to the image you want to process.

2. The cropped image will be saved in the same directory as the input image.

### Usage with Streamlit

1. Install Streamlit:

```bash
pip install streamlit
```

2. Run the Streamlit application:

```bash
streamlit run app.py
```

3. Open your web browser and navigate to the provided local URL (usually http://localhost:8501/) to access the Streamlit app.

4. Upload an image through the provided interface to initiate the document scanning process.

## Contributing

If you'd like to contribute to this project, please follow the standard GitHub fork and pull request workflow.

[streamlit-app-2024-01-04-00-01-92.webm](https://github.com/karansingh21202/Image_crop/assets/131647871/09d4e695-8e3e-4e40-b025-4edf0c71da57)
[streamlit-app-2024-01-04-00-01-38.webm](https://github.com/karansingh21202/Image_crop/assets/131647871/4798880d-5dfc-47c7-81a5-867cdf33da65)
![Screenshot 2024-01-04 000507](https://github.com/karansingh21202/Image_crop/assets/131647871/7376f3ce-1860-4eef-acf2-aeecad7d3fcb)
![Screenshot 2024-01-04 000234](https://github.com/karansingh21202/Image_crop/assets/131647871/d57ec20f-9223-48d1-864c-66e75c7c851d)
![Screenshot 2024-01-04 000124](https://github.com/karansingh21202/Image_crop/assets/131647871/187a2d64-5299-4da3-a324-7d2817124bcd)
![Screenshot 2024-01-04 000040](https://github.com/karansingh21202/Image_crop/assets/131647871/a76db582-5b40-428b-886e-bde191a36030)
![Screenshot 2024-01-03 235918](https://github.com/karansingh21202/Image_crop/assets/131647871/3fddb805-e86d-4abf-9e7a-3a25ae667859)
![Screenshot 2024-01-03 235841](https://github.com/karansingh21202/Image_crop/assets/131647871/a304c9f4-a9f3-4f01-bfcc-ac3f5ae56a5b)
![Screenshot 2024-01-03 235737](https://github.com/karansingh21202/Image_crop/assets/131647871/781d70ba-d1d9-4a88-b193-ce34ae624928)
![Screenshot 2024-01-03 235652](https://github.com/karansingh21202/Image_crop/assets/131647871/619b08d1-343b-4654-9fe8-da4f18501f47)
![Screenshot 2024-01-03 235437](https://github.com/karansingh21202/Image_crop/assets/131647871/f74e253d-ee0f-4eb7-ae08-33d95d01236b)
![Screenshot 2024-01-03 235326](https://github.com/karansingh21202/Image_crop/assets/131647871/ede83807-f457-405a-84c5-3c91b02e555d)
![im](https://github.com/karansingh21202/Image_crop/assets/131647871/7994523a-0ee9-4da8-8f80-973d1e2d25e6)


## Acknowledgments

- [OpenCV](https://opencv.org/) - Computer vision library used in this project.
- [Streamlit](https://streamlit.io/) - Used for creating interactive web applications with Python.
```

Feel free to use and modify this README template according to your specific project details.
