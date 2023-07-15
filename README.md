# shahad
This code will show a GUI in python  allows you to manipulate photos by resizing them, drawing on them, and applying filters and clear it. It uses the Python programming language and the PIL (Python Imaging Library) libraryand tkinter Library .

## Features

- Resize: You can resize an image to a desired width and height.
- Drawing: You can draw shapes, lines, and text on the image.
- Filters: You can apply various filters to the image, such as grayscale, blur, and sepia.
-clear: you can clear the canvsas
## Installation

1. Make sure you have Python installed on your system. You can download it from the official Python website: https://www.python.org/downloads/

2. Install the required libraries by running the following command in your terminal or command prompt:

      pip3 install Pillow
3.   Install the required libraries by running the following command in your terminal or command prompt:

      pip3 install tkinter

## Usage

1. Clone or download the code from the repository.

2. Open the code in your preferred Python IDE or text editor.

3. Import the necessary modules:

      from PIL import Image, ImageDraw, ImageFilter
   

4. Load an image using the Image.open() method:

      image = Image.open("path/to/image.jpg")
   

5. Resize the image using the resize() method:

      resized_image = image.resize((width, height))
   

6. Draw on the image using the ImageDraw module:

      draw = ImageDraw.Draw(resized_image)
   draw.rectangle((x1, y1, x2, y2), outline="red", width=2)
   draw.text((x, y), "Hello, World!", fill="blue")
   

7. Apply filters to the image using the filter() method:

      filtered_image = resized_image.filter(ImageFilter.GaussianBlur(radius=2))
   

8. Save the manipulated image using the save() method:

      filtered_image.save("path/to/save/image.jpg")
   

9. Run the code and observe the manipulated image.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

#reference

https://youtu.be/5V_cPy2dtTc


