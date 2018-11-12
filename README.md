# Neural Style Transfer

I utilized deep learning in order to compose images with the style of another image.

The initialization image usually begins with white noise. Consequently, I decided to also initialize the image with the style image or the content image separately in an attempt to discover which would produce the best image.

After trial and error, I eventually put together various discoveries in order to compose the most clear image that still accurately incorporated the style of the other image. As a result, I used the content image as my initialization image, incorporated a scaling factor of [4,1,1,2,4], and used the ADAM optimization algorithm instead of the classical stochastic gradient descent or LBFGS in order to update the network weights. 

