# 📷 Media Processing Workshop

[![License](https://img.shields.io/github/license/mr-pylin/media-processing-workshop?color=blue)](https://github.com/mr-pylin/media-processing-workshop/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.14.5-yellow?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3145/)
[![Code Style](https://img.shields.io/badge/code%20style-black-black.svg)](https://github.com/psf/black)
![Repo Size](https://img.shields.io/github/repo-size/mr-pylin/media-processing-workshop?color=lightblue)
![Last Updated](https://img.shields.io/github/last-commit/mr-pylin/media-processing-workshop?color=orange)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?color=brightgreen)](https://github.com/mr-pylin/media-processing-workshop/pulls)
[![Telegram](https://img.shields.io/badge/Telegram-Group-black?logo=telegram)](https://t.me/python_topics)
<!-- [![Codacy Badge](https://app.codacy.com/project/badge/Grade/9eb774b7945449cdb86029e9093b3c73)](https://app.codacy.com/gh/mr-pylin/media-processing-workshop/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade) -->

A practical guide to digital image processing, covering essential concepts, algorithms, and real-world applications. Through hands-on exercises and step-by-step explanations, you'll learn how to enhance, transform, analyze, and manipulate images using modern tools and techniques.

## 📖 Table of Contents

### 📘 Essentials

1. [**Complex Numbers & Euler’s Formula**](./code/base/01-complex-numbers.ipynb)
1. [**Linear Algebra Basics**](./code/base/02-linalg-basics.ipynb)
1. [**Introductions to Convolution**](./code/base/03-convolution.ipynb)
1. [**Introductions to Frequency Transforms**](./code/base/04-transforms.ipynb)

### 📖 Main Notebooks

1. [**Introduction to Digital Images**](./code/01-introduction.ipynb)
1. [**Load & Save Images**](./code/02-io.ipynb)
1. [**Common Digital Image Types**](./code/03-common-types.ipynb)
1. [**Interpolating Images**](./code/04-interpolation.ipynb)
1. [**Apply Geometric Transformations**](./code/05-geometric-transformation.ipynb)
1. [**Intensity Transformations**](./code/06-intensity-transformation.ipynb)
1. [**Histogram Processing**](./code/07-histogram-processing.ipynb)
1. [**Spatial Filtering using Convolution**](./code/08-spatial-filtering.ipynb)
1. [**Frequency Filtering using Fourier & Cosine Transform**](./code/09-frequency-filtering.ipynb)
1. [**Multi-Resolution Analysis (Wavelet Transform)**](./code/10-multi-resolution-analysis.ipynb)
1. [**Image Compression (JPEG Coded)**](./code/11-image-compression.ipynb)
1. [**Morphological Processing**](./code/12-morphological-processing.ipynb)

### 📖 Utilities

A collection of concepts and tools utilized in the main notebooks

- [**Color Spaces**](./code/utils/color-space.ipynb)
- [**Introductions to Compression**](./code/utils/compression.ipynb)
- [**All about Paddings**](./code/utils/padding.ipynb)
- [**Quality Assessment Metrics**](./code/utils/quality-assessment.ipynb)
- [**Applying Tone Filters**](./code/utils/tone-filters.ipynb)

### 📖 Projects

- [**DIP 3/e—Student Projects**](./code/projects/dip3e/)
  - A set of student projects from Digital Image Processing, 3rd Edition. [View the projects](https://www.imageprocessingplace.com/DIP-3E/dip3e_student_projects.htm).
  - [**chapter-02**](./code/projects/dip3e/chapter-02.ipynb)

## 📋 Prerequisites

> [!NOTE]
> The mathematics requirements below are **not mandatory** but will significantly deepen your understanding of machine learning concepts.

- 👨‍💻 **Programming Fundamentals**
  - 🐍 Proficiency in **Python** (data types, control structures, functions, classes, etc.).
    - My Python Workshop: [**github.com/mr-pylin/python-workshop**](https://github.com/mr-pylin/python-workshop)
  - 📦 Experience with libraries like **NumPy** and **Matplotlib**.
    - My NumPy Workshop: [**github.com/mr-pylin/numpy-workshop**](https://github.com/mr-pylin/numpy-workshop)
    - My Data Visualization Workshop: [**github.com/mr-pylin/data-visualization-workshop**](https://github.com/mr-pylin/data-visualization-workshop)
- 🔣 **Mathematics for Video Processing**
  - 🔲 **Linear Algebra**: Vectors, matrices, matrix operations.
    - [**Linear Algebra Review and Reference**](https://www.cs.cmu.edu/%7Ezkolter/course/linalg/linalg_notes.pdf) written by [*Zico Kolter*](https://zicokolter.com).
    - [**Notes on Linear Algebra**](https://webspace.maths.qmul.ac.uk/p.j.cameron/notes/linalg.pdf) written by [*Peter J. Cameron*](https://cameroncounts.github.io/web).
    - [**MATH 233 - Linear Algebra I Lecture Notes**](https://www.geneseo.edu/~aguilar/public/assets/courses/233/main_notes.pdf) written by [*Cesar O. Aguilar*](https://www.geneseo.edu/~aguilar/).
  - 🎲 **Probability & Statistics**: Probability distributions, mean/variance, etc.
    - [**MATH1024: Introduction to Probability and Statistics**](https://www.sujitsahu.com/teach/2020_math1024.pdf) written by [*Sujit Sahu*](https://www.southampton.ac.uk/people/5wynjr/professor-sujit-sahu).
- 📶 **Digital Signal Processing Knowledge**
  - [**Digital Image Processing (4th Edition)**](https://www.imageprocessingplace.com/DIP-4E/dip4e_main_page.htm) written by [*Rafael C. Gonzalez*](https://www.imageprocessingplace.com/root_files_V3/about_the_authors/gonzalez.htm) & [*Richard E. Woods*](https://www.imageprocessingplace.com/root_files_V3/about_the_authors/woods.htm)
  - [**The Scientist and Engineer's Guide to Digital Signal Processing**](https://www.dspguide.com/pdfbook.htm) written by [*Steven W. Smith*](https://www.dspguide.com/swsmith.htm)

## ⚙️ Setup

> [!IMPORTANT]
> This project requires Python **v3.10** or higher. For **optimal compatibility** and to **avoid potential issues** with dependencies, it is **strongly advised** that you use the Python version specified in the [**.python-version**](.python-version) file.

### 📝 List of Dependencies

[![imagecodecs](https://img.shields.io/badge/imagecodecs-2026.5.10-008080)](https://pypi.org/project/imagecodecs/2026.5.10/)
[![ipykernel](https://img.shields.io/badge/ipykernel-7.2.0-ff69b4)](https://pypi.org/project/ipykernel/7.2.0/)
[![ipympl](https://img.shields.io/badge/ipympl-0.10.0-purple)](https://pypi.org/project/ipympl/0.10.0/)
[![ipywidgets](https://img.shields.io/badge/ipywidgets-8.1.8-ff6347)](https://pypi.org/project/ipywidgets/8.1.8/)
[![matplotlib](https://img.shields.io/badge/matplotlib-3.10.9-green)](https://pypi.org/project/matplotlib/3.10.9/)
[![numpy](https://img.shields.io/badge/numpy-2.4.6-orange)](https://pypi.org/project/numpy/2.4.6/)
[![opencv-contrib-python](https://img.shields.io/badge/opencv--contrib--python-4.13.0.92-blue)](https://pypi.org/project/opencv-contrib-python/4.13.0.92/)
[![pillow](https://img.shields.io/badge/pillow-12.2.0-cyan)](https://pypi.org/project/Pillow/12.2.0/)
[![PyWavelets](https://img.shields.io/badge/PyWavelets-1.9.0-red)](https://pypi.org/project/PyWavelets/1.9.0/)
[![scikit-image](https://img.shields.io/badge/scikit--image-0.26.0-darkblue)](https://pypi.org/project/scikit-image/0.26.0/)
[![scipy](https://img.shields.io/badge/scipy-1.17.1-purple)](https://pypi.org/project/scipy/1.17.1/)

### 📦 Installing Dependencies

#### 1️⃣ Method 1: uv (**Recommended** ✅)

- Use [**uv**](https://docs.astral.sh/uv/) for dependency management. It handles dependencies, virtual environments, and locking versions more efficiently.
- To install exact dependency versions specified in [**uv.lock**](./uv.lock) for consistent environments **without** installing the current project as a package:

  ```bash
  uv sync --no-install-project
  ```

#### 2️⃣ Method 2: pip

- Install all dependencies listed in [**requirements.txt**](./requirements.txt) using [**pip**](https://pip.pypa.io/en/stable/installation/):

  ```bash
  pip install -r requirements.txt
  ```

> [!CAUTION]
> **pip** does not lock dependency versions as strictly as `uv`. You may encounter version conflicts or reproducibility issues. Only use this method if you know what you are doing.

### 🛠️ Usage Instructions

1. Open the root folder in [**VS Code**](https://code.visualstudio.com/) (`Ctrl/Cmd + K` then `Ctrl/Cmd + O`).
1. Open `.ipynb` files using the [**Jupyter extension**](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) integrated within **VS Code**.
1. Allow **VS Code** to install any recommended dependencies for working with Jupyter Notebooks.
1. Select the correct Python kernel and virtual environment in which the dependencies were installed.

> [!NOTE]
>
> - Stick with the **exact dependency versions** specified in [**uv.lock**](./uv.lock) or [**requirements.txt**](./requirements.txt). The repository has been **tested** with these versions to ensure **compatibility** and **stability**.
> - This repository is **actively maintained**, and dependencies are **updated regularly** to the latest **stable** versions.
> - The **table of contents** embedded within **notebooks (`.ipynb` files)** may not function correctly on **GitHub**.
> - For an improved experience, open the notebooks **locally** or view them via [**nbviewer**](https://nbviewer.org/github/mr-pylin/media-processing-workshop), rather than directly on **GitHub**.

## 🔗 Usefull Links

### Tools

- **ffmpeg & ffprobe**:
  - ffmpeg is a Swiss Army knife for media, converting and manipulating audio and video files in a wide range of formats.
  - Link: [github.com/BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds)

### Benchmark Files

- **DIP3/e — Book Images**
  - A collection of all images and videos used in the **Digital Image Processing (3rd Edition)** book written by [*Rafael C. Gonzalez*](https://www.imageprocessingplace.com/root_files_V3/about_the_authors/gonzalez.htm) & [*Richard E. Woods*](https://www.imageprocessingplace.com/root_files_V3/about_the_authors/woods.htm).
  - Permission is required from the owner of a © image if the image is used for other than personal educational or research purposes.
  - Link: [imageprocessingplace.com/DIP-3E/dip3e_book_images_downloads.htm](https://www.imageprocessingplace.com/DIP-3E/dip3e_book_images_downloads.htm)

### Codecs

- Codecs are algorithms used to **compress** and **decompress** signals, ensuring **efficient storage and transmission of high-quality** signals **e.g. videos**.
- For detailed information on popular image codecs, refer to the [**./codecs/README.md**](./codecs/README.md).

### NumPy

- A fundamental package for scientific computing in Python, providing support for **arrays**, **matrices**, and a large collection of **mathematical functions**.
- Official site: [numpy.org](https://numpy.org/)

### Data Visualization

- A comprehensive collection of Python libraries for creating static, animated, and interactive visualizations: **Matplotlib**, **Seaborn**, and **Plotly**.
- Official sites: [matplotlib.org](https://matplotlib.org/) | [seaborn.pydata.org](https://seaborn.pydata.org/) | [plotly.com](https://plotly.com/)

### OpenCV (Open Source Computer Vision)

- A powerful open-source library (primarily written in C++) for computer vision and image processing tasks.
- Supports a wide range of functionalities, including image and video processing, object detection, facial recognition, and more.
- Compatible with multiple programming languages, including Python, C++, and Java.
- Official sites: [opencv.org](https://opencv.org/)

## 🤝 Contributions & Feedback

- Found an issue, have a suggestion, or wish to contribute? Your input is **highly valued**.  
- Reach out to me via [**linktr.ee/mr_pylin**](https://linktr.ee/mr_pylin).

## 📄 License

This project's code is licensed under the **[Apache License 2.0](./LICENSE)**. This license grants you the freedom to **use**, **modify**, and **distribute** the code. However, any distribution of the code **must** include copies of both the [**LICENSE**](./LICENSE) and [**NOTICE**](./LICENSE) files.

### ©️ Copyright Information

- ✅ **Original Assets**:
  - The assets located in the [**./assets/original/**](./assets/original/) folder are licensed under the **[CC BY-ND 4.0](./assets/original/LICENSE)**.
  - Note: This license restricts derivative works, meaning you may share these assets but cannot modify them.

- 🌐 **External Assets**:
  - The assets located in the [**./assets/external/**](./assets/external/) folder are collected from multiple third-party sources.
  - Each subfolder within [**./assets/external/**](./assets/external/) contains its own `ATTRIBUTION.md` file detailing the relevant copyright, license, and attribution information for the assets within that specific subfolder.
  - Users must review the applicable `ATTRIBUTION.md` file before using, redistributing, or modifying any external asset.

### ⚠️ Concerns & Reporting

- If you are a copyright holder and believe that any asset in this repository has been included improperly or without appropriate attribution, please contact the repository maintainer.
- Upon verification, the content will be promptly corrected or removed as necessary.
