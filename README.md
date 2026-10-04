# Teach a Machine!

An introductory tutorial for building an image classification application with **Google Teachable Machine + Scratch**, using the TM2Scratch extension in Stretch3. No prior coding experience is required.

Created for **EDUS 268: AI & ML in Education** at Virginia Commonwealth University.

**Instructor:** Dr. Chi-Ning (Nick) Chang

## What you will learn

The 21-slide tutorial guides students through collecting training examples, training a model, testing predictions, finding errors, exporting the model, and using its predictions in a Scratch application.

It includes simple explanations of **epochs, batch size, learning rate, confidence, and accuracy**, followed by instructions for recording sounds and a line-by-line walkthrough of the example Scratch scripts. The final slides explain how a variable and conditions control repeated responses and provide a downloadable `.sb3` example.

## Open the tutorial

Download `index.html` and open it in a browser such as Chrome. The screenshots, 22-second opening video, and downloadable Scratch example are embedded in the HTML file.

- Use the **left and right arrow keys** or **Back / Next** buttons to change slides.
- Use the slide selector to jump to a specific slide.
- Click a screenshot to enlarge it.
- Click the video’s play button to watch the opening demonstration.

To publish with GitHub Pages, open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/ (root)**, and save.

## Try the activity

1. Open [Google Teachable Machine](https://teachablemachine.withgoogle.com/) and create an **Image Project → Standard Image Model**.
2. Collect examples for clearly different classes, then train and test the model.
3. Export with **TensorFlow.js → Upload my model** and copy the model URL.
4. Open [Stretch3](https://stretch3.github.io/) in Chrome and add the **TM2Scratch** extension.
5. Load the model URL and connect class labels to sound recordings or speech bubbles.

[Try Nick’s example model](https://teachablemachine.withgoogle.com/models/w_DQ4_ljC/). This demonstration model is not perfect. Test its limitations and consider how its training data could improve.

To inspect the example project, download the `.sb3` file from **Slide 21**, then open it in Stretch3 using **File → Load from your computer**. Allow camera access and click the model URL block to load the model.

## Resources and acknowledgments

- [Teachable Machine FAQ](https://teachablemachine.withgoogle.com/faq)
- [TM2Scratch documentation and source code](https://github.com/champierre/tm2scratch)
- [TensorFlow: training, epochs, and batches](https://www.tensorflow.org/guide/keras/training_with_built_in_methods)
- [TensorFlow: learning rate](https://www.tensorflow.org/guide/core/quickstart_core)

Screenshots, opening video, and example Scratch project supplied by Nick Chang.

TM2Scratch is licensed under **AGPL-3.0**. Copyright © 2020 Junya Ishihara and Koji Yokokawa. That license applies to TM2Scratch and does not establish a license for this tutorial.
