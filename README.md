# Starter for deploying [fast.ai](https://www.fast.ai) models on [Render](https://render.com)

This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

The sample app described here is up at https://fastai-v3.onrender.com. Test it out with bear images!

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.



# The pre-trained model was built and powered by fastai framework.
1. download the urls from google images
2. label and store the data into different folders
3. define the neural network framework
4. load the data into framework
5. train and observe the result
6. tune the model by adjusting the learning rate, removing the dirty data etc
7. export the model
8. publish to web app

Added: due to the limited the sample data, face recognition works well on the training set, but would be difficult to distinguish the
slightly differences between the face expression. 

-- change to pet classification
