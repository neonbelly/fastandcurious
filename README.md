# Fast And Curious
304 class car classification app using neural networks, Keras, CoreML, and Swift.
Using a pretrained ResNet50 neural network, we can add a few additional layers and train on car model data.
Once the model is trained, it is as simple as converting the model to CoreML using coremltools and then designing an iOS app around the model.


## View my presentation here:

[![Youtube](https://i.pinimg.com/originals/47/bb/4c/47bb4ca2b686e732a0817e76c1f6acf1.png)](https://youtu.be/Dy2bQKBpesU "Fast and Curious")

## iOS App Demo

![](app_demo.gif)

## Technologies Used:
* https://www.kaggle.com/austinreese/craigslist-carstrucks-data (images scraped using urls from this dataset via urllib)
* Google Compute Engine (Processing)
* Keras, ResNet50, CoreML (Neural Network)
* ![coremltools](https://apple.github.io/coremltools/generated/coremltools.converters.keras.convert.html "coremltools")
* Swift (iOS app)
