Visual-Theme-Interpreter
his tool creates a custom **UI theme configuration** using an image and a short text prompt. It analyzes the image’s main color and meaning to generate a `.json` theme file.
What It Does

- Extracts **dominant color** from the input image
-  Reads any **text** in the image (OCR)
- Uses **CLIP** to understand the image + prompt together
- Generates a theme config (colors, font style, etc.)
Requirements
torch

sentence-transformers

openai-clip

easyocr

opencv-python

pillow


