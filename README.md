An AI based interface which generates 3D DISNEY PIXAR stickers according to the image and prompt given.

While programming we began by using the HUGGING FACE reference and inculcated the stable diffusers model which was not able to provide us with the desired result.

Therefore we moved towards the stable diffusers XL model, but the XL model required heavy processing and a lot of storage, which was not possible on VSCode, so we shifted to Google Collab. But, we still faced problems using SDXL model.

Our second approach to our problem was that we divide the problem into two halves - in the first half, our program will read the image and generate an output, for which we will subsequently use an image to text model and for the second, our program will generate a prompt keeping in mind the characteristics and features of the original image, for which we would use a text to image model.

However, we used the pix 2 pix model which was highly sustainable and provided us with the desired result. For the prompts, we tried inculcating OPEN AI, so that the user may prompt "Good Night" and the AI will be able to produce a person lying on the bed sleeping or tucked in bed etc.

We were successfully able to achieve the desired results as shown below.

Here is a prototype of it.
![image](https://github.com/user-attachments/assets/4c236740-cbef-463d-b7a9-d18b6ca8c0ac)
![image](https://github.com/user-attachments/assets/6b2298b9-e411-4c2c-9d49-8665e78f8a54)
![image](https://github.com/user-attachments/assets/a226e794-58c1-4be3-90c2-0f49d734abfb)
![image](https://github.com/user-attachments/assets/5c2c597f-5694-438a-8b59-0703a92c26f0)

GRADIO INTERFACE - An interface designed specifically so that user can upload their image and recieve the desired output.
![image](https://github.com/user-attachments/assets/1f9d88bd-39bf-4546-a901-6541d11b0735)




