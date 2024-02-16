<!-- TOC -->
* [Introduction](#introduction)
* [Copy this structure - TODO - remove after initial setup](#copy-this-structure---todo---remove-after-initial-setup)
* [Folder structure](#folder-structure)
  * [data](#data)
    * [input](#input)
    * [intermediate](#intermediate)
    * [output](#output)
  * [documentation](#documentation)
  * [models](#models)
  * [notebooks](#notebooks)
  * [scripts](#scripts)
  * [Additional files](#additional-files)
    * [.gitattributes](#gitattributes)
    * [.gitkeep](#gitkeep)
    * [.gitignore](#gitignore)
    * [environment.yml](#environmentyml)
    * [README.md](#readmemd)
    * [settings.json](#settingsjson)
* [Project information - TODO](#project-information---todo)
* [Resources - TODO](#resources---todo)
<!-- TOC -->


# Introduction
This repo was made for the Data Science course from AB Syntra, Numpy project: https://github.com/ypottiez/Numpy-Project
Data and code can be freely used an redistributed with or without changes, no license applied.

# Folder structure
Below you will find more information on how the project folder structure was set-up and where to find and store the appropriate files.


## data
Data files can be found in this folder structure in the correct sub-folder as described in the next sub-chapters.

### input
Raw/unchanged files as provided or downloaded.
Changes to dataset will not be saved here to prevent mistakes from happening.

### output
Data that does not need processing anymore but can directly be used.
Reports/plots/... can also be stored as final products.

## documentation
Additional information and guides to help people get started.
Slides, PDFs, User Stories, UML diagrams, ... can be stored here as well.

## notebooks
In this folder we save Jupyter notebooks used for analysis, visualization and experimentation.

 ## Additional files
 In this chapter we are discussing files that are situated in your project root folder and other folders.

### .gitattributes
Defines which files should be tracked by Git LFS (Large File Storage).
This is useful for large files like datasets, models, etc...
Execute 'git lfs install' on your local machine in the directory of your project to activate Git LFS.

### environment.yml
Contains the information about the conda environment.
This file can be used to create a new environment with the same packages as the original environment.
Execute `conda env create -f environment.yml` to create the environment.
Use `conda activate syntra_minimal` to activate the environment.

### README.md
Markdown file with information about the project, contains the information you are reading now.

 


 # Project information - TODO
 The purpose of this project is to find a random image and create a series of demanded and chosen manipulations as described in asignment.pdf (see documentation folder)

 # Resources - TODO
 Add resources used in the project

 - Github markdown: [guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
 - Gitignore generator: [gitignore.io](https://www.toptal.com/developers/gitignore/)


 # Image Manipulation Toolkit

## Description
The Image Manipulation Toolkit is a Python program that provides a collection of tools for performing various image manipulation tasks. It includes functionalities to resize images, apply filters, adjust colors, and perform other common image processing operations.

## Installation
To use the Image Manipulation Toolkit, follow these steps:

1. Clone the repository to your local machine:
git clone https://github.com/username/image-manipulation-toolkit.git

## Usage
To run the program, execute the `main.py` script and specify the desired image manipulation operation along with any optional parameters.

Example usage:
python main.py --operation resize --input image.jpg --output resized_image.jpg --width 800 --height 600

markdown
Copy code

Supported operations:
- `resize`: Resize an image to the specified dimensions.
- `filter`: Apply a filter (e.g., blur, sharpen) to an image.
- `color_adjustment`: Adjust the color balance, brightness, and contrast of an image.

For more detailed usage instructions and available options, run:
python main.py --help

less
Copy code

## Examples
### Resize Operation
Original Image:
![Original Image](examples/original_image.jpg)

Resized Image:
![Resized Image](examples/resized_image.jpg)

### Filter Operation
Original Image:
![Original Image](examples/original_image.jpg)

Filtered Image (Blurred):
![Filtered Image](examples/blurred_image.jpg)

### Color Adjustment Operation
Original Image:
![Original Image](examples/original_image.jpg)

Color-Adjusted Image (Increased Contrast):
![Color-Adjusted Image](examples/color_adjusted_image.jpg)

## Contributing
If you'd like to contribute to the Image Manipulation Toolkit, please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, contact the project maintainer at [email@example.com](mailto:email@example.com).
