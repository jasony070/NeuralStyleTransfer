# CS 152
# Assignment 3
# October 10, 2018
##  Due October 23, 2018, 11 PM

In this assignment, you’ll work with Neural Style Transfer.  You can work individually or in pairs, but if you work in pairs, all work must be done while you are physically together, working on one computer with one keyboard and mouse, switching off the driver.

Since there are two weeks for the assignment, rather than the customary one week, there will be no extensions granted.

Things you’ll need:

* The [Style Transfer notebook](https://github.com/nrhodes/cs152/blob/master/notebooks/StyleTransfer.ipynb) used in class.
* A Github account
* A machine with a GPU (Google Cloud Platform, or personal machine)

Things you’ll need to do:

* Join a team on Github (follow the invitation link sent via email).
* Launch your GPU machine and do a ```git pull``` on the cs152 git repository to get the latest files. 
* Get your GPU machine running Jupyter Notebook.
* Clone your team repository.
* Do your work in the Python notebook assignment3.ipynb
* Create a version of the notebook that just does style transfer onto a content image (no copying content to a random image, or style to a random image). Your notebook should be clean and minimal. Feel free to refactor
  the given code to make it simpler or more readable (e.g., you may choose to create new functions or classes).
  Blindly copying and pasting from the given notebook will not be your best bet. Make sure you understand all the code you have in your notebook.
* Make the following additions to your code. For each one, make sure you are displaying the output image produced.
    * Make the style loss incorporate a scaling factor for each layer so that you can adjust how important each layer's activations are, and then test various values for those scaling factors, seeing which is most pleasing.
	* Use a different style image with the same content.
	* Use a different content image with the same style.
	* Use a different optimizer (instead of LBFGS).
	* Rather than initializing with a random image, try initializing with:
	    * the content image
		* the style image
	* Show the best image you can come up with, using the original style and content images, changing whatever hyperparameters you need (e.g., learning rate, number of optimization steps, scaling factors). Do not feel you need to spend hours on this part.  Although I won't be explicitly grading on how good your image is, I may award bonus points to one team if they have a particularly good image. 
* Commit your notebook and push it to Github.
* Check the result on Github to make sure it matches what you think it should.

## Submission details

Start your notebook with a list of your team members. Make sure that the notebook documents not only the code that has run, but also documents what you are doing and why. 

Commit your Jupyter notebook (```assignment2.ipynb```) to Git and push it to GitHub. You only need one submission per team, and the last commit on GitHub before the due date will be your submission.

I'll be printing the notebook from Github in order to grade it, so ensure that it looks good there.

