# handwritten-recognition

An interactive application that recognizes handwritten digits using a pre-trained TensorFlow/Keras model with a Pygame interface.

-----Features
Interactive Canvas: Draw digits with your mouse
Real-time Recognition: Classify handwritten digits (0-9)
Simple Controls: Reset canvas with one click
MNIST-Compatible: Works with standard 28x28 digit recognition models

------How to use
1.Firstly, satisfy all the requirements by using:
pip install -r requirements.txt

2. Then, train the model by using:
python handwriting.py mymodel.keras
(if you dont wanna train, you can use the trained model)

3. Test:
python recognition.py mymodel.keras
The window will come out automatically
