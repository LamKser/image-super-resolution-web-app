# Deploy SRGAN model using Flask
You can visit our SRGAN model [here](https://github.com/LamKser/Image-super-resolution-using-GAN)
* `app.py` - Run web
* `uploads`, `enhance` - Save image that you load from the computer and image after enhancing
* `model` - Save the model architecture and weights
* `templates` - HTML file
* `Procfile`, `requirements.txt`, `Update requirements.txt`, `runtime.txt` for deploying on [Heroku](https://www.heroku.com/home) 
### Demo
Run `app.py` - (I'm running localhost)
<div align="center">
  <img src="/test_images/Test_web_1.png" width="80%" height="80%"">
</div>

Choose `Choose file` and select image you want to enhance. Then press `Enhance` button

<div align="center">
  <img src="/test_images/result.png" width="80%" height="80%"">
</div>

# Code reference:
Web: [:link: Youtube](https://www.youtube.com/watch?v=dP-2NVUgh50&t=6s&ab_channel=RedEyedCoderClub)
