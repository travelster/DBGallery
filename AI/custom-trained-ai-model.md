---
layout: default
title: Custom Trained AI Model
permalink: /custom-trained-ai-model
parent: AI
grand_parent: DBGallery
nav_order: 30
---

# Custom Training AI Model

To use your own custom trained object detection model, simply enter the model's ARN (Amazon Resource Name) in DBGallery: Go to Tools / Preferences, then the Advanced tab.  Set the 'Custom object recognition' checkbox and enter the model's ARN, as shown below.

With this information entered, DBGallery will then send uploaded images to that model for object detection.

<p style="margin-left: 5%;"><img style="border: 1px solid grey;" width="100%" src="/assets/object-recognition-settings.png" alt="Custom AI model settings"/></p>


## Using the Model
Because running a custom model entails <a href="https://www.techtarget.com/whatis/definition/What-is-AI-inference" target="blank">inference</a> costs, it is turned off until needed.  With it being off, it can take up to 30 minutes for images to start being recognized.  This is the wait time required for the model to start.  DBGallery automatically starts the model when any object recognition is requested.  This is usually during upload, but can also be manually trigged in the UI for images already uploaded.  Once all images have run through the object recognition process, DBGallery will automatically stop the model after 5 minutes.  The 5 minute delay allows time for more requests to avoid needing to wait for the model to start again.

## More Info
For more on this topic, please see our blog post <a href="https://dbgallery.com/custom-ai-object-detection">Custom-trained AI object detection in DBGallery</a>.

If needed, DBGallery consultants are available to help with model training.

