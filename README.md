[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/raphaelquast/jupyter_notebook_intro/master)


# jupyter_notebook_intro
A short introduction to jupyter notebooks

To have a look at the notebook, and get introductions how to set it up locally, 
just click at the **[jupyter_nb_introduction.ipynb](jupyter_nb_introduction.ipynb)** file 
(GitHub should render it automatically)


## Using Binder to run the notebook without a local installation
To try jupyter notebooks **without installing anything locally**, click on the "launch binder" icon above
and wait for the server to complete setting up the environment. 
(this **might take several minutes** since the python environment etc. has to be set up on a server with **limited resources**)

Once it's completed you should arrive at a page looking something like this  
(completely similar to what you would get by using a local installation):

![jupyter-page](jupyter_page.PNG)

- click on the **jupyter_nb_introduction.ipynpl** file and select **kernel** -> **Restart & Run All** to execute the notebook

![jupyter-page](jupyter_page_2.PNG)

- click on the Rise-icon on the right ![Rise-icon](rise_icon.png) to start the notebook as an interactive HTML-presentation 


### Enable scrolling the presentation slides
some slides might be to large for your screen. (particularly those that contain code-cells)

in order to enable scrolling the slides go to the **nbextensions** tab and click on **Rise**
![jupyter-page](nbextensions.png)

Then navigate down to the following line and activate *scroll*
![jupyter-page](scroll.png)

Now, re-open the notebook to have a scrollable presentation!
