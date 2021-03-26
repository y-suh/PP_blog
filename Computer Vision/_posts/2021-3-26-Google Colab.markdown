---
layout: single
classes: wide
title:  "Google Colab"



header:
  teaser: /assets/images/google.png
  overlay_image: /assets/images/google.png

excerpt: "Work at home"

permalink: /computer-vision/google-colab/
---

## What is Google Colab ##

<figure style="width: 900px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/google.png" alt="">
  <figcaption></figcaption>
</figure> 

Google Colab, or 'Colab' for short, is a product developed by the Google research team. Colab allows anyone to write and run arbitrary Python code through a browser. Colab is especially suitable for machine learning, data analysis and training. More technically, Colab is a hosted Jupyter notepad service that can be used without any setup, providing free computing resources including GPUs.

So basically, it is a platform where we have shared access to really, really good GPUs which can be accessed through the Colaboratory Notebook. If you are familiar with Jupyter Notebook, then great! This is exactly the same.



## The Setup ##

To access Google Colab, just search for it on google and it should be the first link that pops up. Once you enter you will have to sign in and link Colab with your Google account. 



#### Setting up Runtime

After you link your account, go to files and make a new note. 

To do this, clock on `Runtime` located on the top toolbar. Then click `Change runtime type`.

`Runtime` -> `Runtime type`

You will be able to select `GPU` as your Hardware accelerator. If you choose none, it will based on CPU. 



#### Connecting to the platform

Now, let's connect the notebook. On the top right corner of your window, you will see a `Connect` button. Click it. If you see the Ram and Disk menu pop up, you are good to go!



#### Importing data from Google Drive

The step we are about to do will connect your Colab notebook with Google Drive. You will have access to all the data you have stored here. What's really good is that we can basically share datasets by uploading them into shared Google Drive folders.

Run the following command in the code cell.

```
from google.colab import drive
drive.mount('/content/drive')
```

The first time you do this, you will be provided a url where you will be asked to sign in and permit access to your Google Drive account. Once you go through that process, copy and paste the `authorization code` in Colab. 

Done!

`Mounted at /content/drive` means that you have successfully connected your Google Drive account. If you navigate towards

Now you are all set to go!

<figure style="width: 900px" class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/colab.PNG" alt="">
  <figcaption></figcaption>Here is the snapshot of the button locations!
</figure>