# ImageGenerationProject
This is a console application -Image Generation Project from SoftUni Advanced course with Python. Main purpose is to learn Tkinter

![image](https://github.com/IvanVakov/ImageGenerationProject/assets/119103300/02eb4525-f666-4a26-87f1-88d885805732)

This code is a simple image generator that uses the OpenAI API to generate images based on a given prompt. Here's a breakdown of the code:

The code imports the necessary libraries: os.path for handling file paths, re for regular expressions, random for generating random numbers, urllib.request for making HTTP requests, openai for interacting with the OpenAI API, and tkinter for creating a graphical user interface (GUI).

The OpenAI API key is set using openai.api_key to authenticate API requests.

The MEDIA_FOLDER variable is defined as the folder where the generated images will be saved.

The convert_to_image_object function takes an image URL, downloads the image data, and converts it into a PIL Image object.

The display_image function takes an Image object and displays it in the GUI using Tkinter.

The save_image function takes an Image object and a file path, and saves the image to the specified path. If a file with the same name already exists, a random number is appended to the image name to avoid overwriting.

The get_image_url function sends a request to the OpenAI API to generate an image based on the text entered in the input field. It returns the URL of the generated image.

The render_image function is called when the "Create" button is clicked. It retrieves the generated image URL, converts it to an Image object, displays the image in the GUI, and creates a "Save" button to save the image to the specified folder.

The Tkinter GUI window is created with the title "Image Generator" and dimensions 500x350.

The image label, input field, and "Create" button are placed in the GUI window using Tkinter's place method.

The save_button is initially created without a command. It will be updated dynamically when an image is generated.

The Tkinter main loop window.mainloop() is executed to start the GUI application and handle user interactions.

![image](https://github.com/IvanVakov/ImageGenerationProject/assets/119103300/85edddd1-9751-4d2f-89d7-9a8f29456012)

![image](https://github.com/IvanVakov/ImageGenerationProject/assets/119103300/fd2ec18a-da75-42ec-bbd6-c6eb6eeef66a)


# Live Demo

You can try the console app directly in your Web browser here:

# first open <a href="https://replit.com/@Ivakov/Image-generator#main.py">this link<a/> and put your own key - here openai.api_key = ""
  
Click Run to start the generator
  
![image](https://github.com/IvanVakov/ImageGenerationProject/assets/119103300/bf74a3c5-3885-419c-b36f-dbd4af1284fa)
  
![image](https://github.com/IvanVakov/ImageGenerationProject/assets/119103300/db8d03fb-8637-4f74-ae34-b10625abfda1)




