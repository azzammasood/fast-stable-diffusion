# Fast Stable Diffusion using Dreambooth and Automatic111 Web UI

Starting from Textual Inversion which learns new words in its embedded space that can represent a new image/concept of an object or style that the user provides. Going further, changes over the codebase of Textual Inversion are done to implement Google's Dreambooth on Stable Diffusion. It enables enable people to fine-tune a text-to-image model with a few examples.

* A Google Drive account is mounted and that is where the trained model will be saved. 
* The Stable Diffusion v1.5 model is downloaded from HuggingFace. 
* A folder is created in GDrive where the current session will be saved. 
* There is also the option of loading a previous session by inputing the name or the link of the previous session. 
* Next, the training images are uploaded. These images must be in RGB format. They are resized to 512x512. 

![image](https://user-images.githubusercontent.com/98682258/217756419-e6956272-7ca2-4bf3-8372-2a46298c15df.png)


![image](https://user-images.githubusercontent.com/98682258/217757070-7e105258-1dbd-4082-9926-e9f7cf89ec82.png)


![image](https://user-images.githubusercontent.com/98682258/217756510-b01421bb-ff19-4457-b9e4-fc33ee15e336.png)
