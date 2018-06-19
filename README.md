[T-sne visualization of face embeddings](https://medium.com/@evanescence1106/t-sne-visualization-of-face-embeddings-4e3b5fe611de)

***
We will see how can we extract face embeddings from images using dlib and visualize the same.

![screen shot 2018-06-19 at 11 11 42 am](https://user-images.githubusercontent.com/5259061/41584770-c10e9446-73c5-11e8-9265-473b312699ff.png)
![screen shot 2018-06-19 at 12 13 48 pm](https://user-images.githubusercontent.com/5259061/41584771-c170a14a-73c5-11e8-9fc1-be4d1644a4d0.png)

Run code in the python notebook to generate embeddings.


#Run command below to visualize the tensboard. Replace the logdir path with your custom path


tensorboard --logdir=/Users/anshu/meet-up/internship/recognition/face-embeddings/embeddings-logs/ --port=6006
