# Auto Encoders

![1_nEtqhS8KEo39qwqj-MuLsg](https://user-images.githubusercontent.com/63863911/197867214-2834cbf7-9fa9-4e3b-9a99-df30d232ba4a.png)


Lets take two images -


Noisy input -------------------> ![image_00003](https://user-images.githubusercontent.com/63863911/197867705-fb2dd94a-54fa-499b-a433-55b8a1ae92ce.png) -------------------> Clear output ----------------> ![image_00003 (1)](https://user-images.githubusercontent.com/63863911/197868099-03172dca-5dbd-4b2f-8938-0f3a65173da6.png)

To achieve this we need a encoder and a decoder .A encoder extracts meaningful features from the image while the decoder upsamples the image to its original size so as to produce a new image . Seeing the model architecture one might have a good understanding of the dimensions involved.


![model_ae](https://user-images.githubusercontent.com/63863911/197876651-48882265-9bd5-4a8c-bb23-fae797f24e08.PNG)


When dealing with encoders and autoencoders the most important things to keep in mind are the loss functions and the activation functions involved.
