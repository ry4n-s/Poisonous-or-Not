## 🐍 Poisonous or Not? - A Snake Classifier

### Overview:
A Python-based AI model to differentiate between poisonous and non-poisonous snakes using FastAI. The model is trained on images retrieved from DuckDuckGo, encompassing various scenarios like wild and zoo settings.

### Features:

1. **Automated Image Retrieval**: Uses the DuckDuckGo API to fetch images of snakes based on search terms. It can categorize searches for broader accuracy, i.e., by wild, zoo, and general categories.
   
2. **Data Preprocessing**:
    - Automatically checks for internet connectivity.
    - Image resizing and cleaning (removes improperly downloaded images).

3. **AI Model**:
    - Utilizes the FastAI library.
    - Employs the ResNet18 architecture for efficient and speedy training.
    - Outputs both the prediction (poisonous or not) and the probability/confidence of the prediction.

### Results:
The model has been tested on various snake images, outputting the probability of the snake being non-poisonous. For instance, an image of a non-poisonous snake was correctly identified with a confidence of 100%.
