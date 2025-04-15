🧮 Air-Compute
📝 Overview
The Air-Compute Calculator is an innovative project that utilizes OpenCV and Google’s Gemini AI to solve mathematical problems of any complexity. The user can draw the math problem on the screen, and the AI model will interpret the visual input to provide a detailed solution. This project is similar to the Apple iPad calculator but leverages advanced AI technology for enhanced functionality and accuracy. It also accepts soft copies of math problems and gives you the ai powered solutions .

✨ Features
✍️ Draw/Upload Math Problems: Use your finger to draw any mathematical problem on the screen or upload a soft copy of the math problem.
🖱️ Move Around: Move the pointer around the screen by lifting two fingers.
🗑️ Reset Canvas: Erase the current drawing by lifting the thumb.
📤 Send to AI Model: Send the visual drawing to the model by lifting the little finger.
📊 Detailed Solutions: The model interprets the drawing and displays a detailed solution.
📋 Requirements
🐍 Python 3.x
👁️ OpenCV 4.8.0.74
➗ Numpy 1.23.5
🖼️ Pillow 9.3.0
🤖 Google Generative AI 0.1.0
🛠️ CVZone 1.5.6
🌐 Django 4.2
🚀 Installation
Obtain the Gemini API Key:

Visit AI Studio to get your Gemini API key.
Install Dependencies:

Run the following command to install the required packages:
pip install -r requirements.txt
Configure the API Key:

Add your API key to videoapp/view.py.
Run the Web Application:

Start the web server with:
python manage.py runserver
Access the Web Application:

Open your web browser and navigate to http://127.0.0.1:8000 to use the app.
🎨 Drawing Rules
To interact with the calculator, follow these drawing rules:

✍️ Draw math problems only when the pointer finger is up.
🖱️ Move around the screen by lifting two fingers.
🗑️ Reset/erase the canvas by lifting the thumb.
📤 Send the visual drawing to the AI model by lifting the little finger.
The AI model will then interpret the drawing and display a detailed solution.
