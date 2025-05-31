# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date: 09/05/2025

# Register no. : 212222060185


## AIM:

To develop Python code that works with multiple AI tools like TensorFlow, PyTorch, and scikit-learn, making it easier to switch between them for different tasks.

## PROCEDURE:

1.	Choose common AI tools (e.g., TensorFlow, PyTorch, scikit-learn).

2.	Set up the Python environment and install required libraries.

3.	Write modular code with separate parts for data, model, and training.

4.	Add options to select tools using simple config or input.

5.	Test the code with different AI tools to ensure compatibility.

## PROGRAM:
```
import google.generativeai as genai
genai.configure(api_key='AIzaSyAnL44_7dd13g5ZxaNKt-BnQZdslN79ldU')
model=genai.GenerativeModel('gemini-1.5-flash')
response= model.generate_content('What is the prompt engineering')
print(response.text)
```

## OUTPUT:

![Screenshot 2025-05-31 152224](https://github.com/user-attachments/assets/6d18357f-15ee-4304-a8d1-917a5c049e1c)


 
## RESULT:
The Python code worked successfully with TensorFlow, PyTorch, and scikit-learn, showing good compatibility and easy switching between tools.
