**Sports Detection** - A web application that detects sports(Giant slalom, Skii, Snowboarding, Speed skating and rollerblade racing) based on machine learning. 
It is to classify the pictures and make predictions. Web Bootstrap takes the machine learning model created in **[Lobe](https://lobe.ai/)**, 
and adds it to a project in the browser that uses **[React](https://reactjs.org/)**, **[Create React App](https://github.com/facebook/create-react-app)**, 
**[TypeScript](https://www.typescriptlang.org/)**, and **[TensorFlow.js](https://www.tensorflow.org/js)**.

# Sports Detection

**Developed by** Mr.THINNAPHAT SODANAT, Code. 613040490-0, Computer Engineering, Khon Kaen University.

## How to run Sports Detection on your computer (local server)
1. You need to download this project on your computer. **(make sure you download from branch Master)**
2. You need to install **[Node.js](https://nodejs.org/en/)** - to start the React app or start the local server.
3. In your project's folder, use command **"npm install"** and then use command **"npm start"** to start the local server and redirect to Sports Detection.

## About the project
**1. Train model**
- Use more than 100+ pictures for each sports(Giant slalom, Skii, Snowboarding, Speed skating and rollerblade racing).
- Use model in Lobe(ResNet-50V2) optimize for accuracy.
- Split data at 80/20

**2. Test model**
- 99% of images are predicted correctly.
- 1% are incorrectly.