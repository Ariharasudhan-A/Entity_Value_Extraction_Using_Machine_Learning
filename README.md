# Entity Value Extraction Using Machine Learning

## Overview

The objective of this project is to extract entity values such as item weight, height, voltage, etc., from images of product covers or product images with dimensions. This is achieved using OCR techniques for text extraction from images, followed by a prompt-tuned large language model (LLM), specifically **Gemme-2-2B**, for value extraction from the text.

The project involves:

- **Data Collection**: Gathered a total of 260,000 images with the corresponding entity names from the Amazon website.
  
- **Data Extraction**: Utilized **Paddle OCR** for extracting text from the images.
  
- **Prompt Tuning**: Employed regex patterns in Alpaca prompt format for tuning the Gemma-2-2B model.
  
- **Entity Extraction**: Implemented the prompt tuned Gemma-2-2B model to extract entity values based on predefined regex patterns.

## Data

You can find all the files related to this project [here](https://drive.google.com/drive/folders/1dp2gcMbzfNw560pne8zdnxniH72sUNwn?usp=sharing).

Note: You can download the images using the links in the "image_link" column of the CSV's.

## Results

We Achieved an accuracy of **50.45%** in the entity extraction process, highlighting the model's effectiveness in capturing relevant data from diverse product images.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any queries or contributions, feel free to reach out to:
- **Ariharasudhan A** - [Email](mailto:ariadaikalam1234@gmail.com)
- **Harish R** - [Email](mailto:harishsekar2004@gmail.com)
