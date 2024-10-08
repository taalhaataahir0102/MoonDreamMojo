# MoonDreamMojo
Moondream is a multimodal tiny language vision model with 1.6B parameters, designed to handle both text and image inputs, generating text-based outputs such as captions or responses based on the given input. Here the inference model has been entirely implemented in Mojo, while pre-processing (such as tokenization) and post-processing are handled in Python. The original model implemented in Pytorch can be found [here](https://github.com/vikhyat/moondream)
## How to use the model:
1. Clone the repo:

   ```git clone https://github.com/taalhaataahir0102/MoonDreamMojo.git```

2. Download the weights file from [here](https://drive.google.com/file/d/1Z2AJtBZuWO2gBgzJdaMOJ0aZeNiBnQQv/view?usp=sharing).

3. Extract the weights file in the same directory.

4. make executable run file

   ```chmod +x run.sh```

5. Run the model using:

   ```./run.sh```

Model will ask for the input image and question. 
## Requirments:
RAM: 16 GB

Hard-disk space: 10 GB
## Examples:
![Alt Text](assets/flower.jpeg)

**Question:** What is the flower wearing?

**Answer:** The flower is wearing sunglasses.

![Alt Text](assets/example.jpeg)

**Question:** Describe the image

**Answer:** The image features a group of three paper sculptures of animals, including an elephant, a zebra, and a lion, set against a backdrop of a sunset. The sculptures are arranged in a way that showcases the animals together in a natural setting.
