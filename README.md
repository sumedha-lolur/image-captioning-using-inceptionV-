## Image Caption Generator with InceptionV3 and Gemini Vision Pro

This repository provides two approaches for generating image captions: using a trained InceptionV3 model and leveraging Google's powerful Gemini Vision Pro API.

### Project Goals

* Develop an image captioning tool that generates concise descriptions of uploaded images.
* Offer users a choice between two captioning methods:

    1. **InceptionV3 Model (Optional):** Train a custom InceptionV3 model on a provided dataset (e.g., Flickr8k) for image captioning.
    2. **Gemini Vision Pro API:** Utilize the pre-trained Gemini Vision Pro model through its API to generate captions. Additionally, explore the potential for customizing captions with Gemini Pro.

### Functionalities

* User uploads an image.
* **InceptionV3 (Optional):**
    * Trained model analyzes the image content.
    * Generates a caption describing the image.
* **Gemini Vision Pro:**
    * API call sends the image to Gemini Vision Pro.
    * Receives a short description of the image content.
    * (Future Implementation) Explore options for customizing captions with Gemini Pro.

### Benefits

* Automates image description for tasks like image organization or accessibility.
* Enhances user experience by providing captions for visual content.
* Offers users a choice based on their needs and preferences (custom-trained model vs pre-trained API).

### Getting Started

This repository provides the framework for both approaches. Refer to the specific folders for setup instructions:

* **inceptionv3_captioning (Optional):** Contains code and instructions for training the InceptionV3 model on a dataset.
* **geminivision_captioning:** Provides scripts and instructions for using the Gemini Vision Pro API for image captioning.

### Dependencies

* (For InceptionV3) TensorFlow, Keras
* Additional libraries may be required based on your implementation choices. Refer to the specific folder documentation for details.

### Usage

1. Clone the repository.
2. Follow the setup instructions in the relevant folder (inceptionv3_captioning or geminivision_captioning).
3. Train the InceptionV3 model (optional) or set up access to the Gemini Vision Pro API.
4. Run the provided script to test the image captioning functionality.

### Contributing

We welcome contributions to this project! Feel free to create pull requests with improvements, bug fixes, or new features. 

### Disclaimer

Using the Gemini Vision Pro API might require specific permissions or incur costs. Refer to Google's documentation for details.
