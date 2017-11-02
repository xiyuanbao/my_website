+++
date = 2017-09-20
lastmod = 2017-09-30
draft = false
tags = ["machine learning", "course project"]
title = "Touch location learning of phone screen basing motion sensors"
math = true
summary = """
Final course project of Principles of artificial intelligence  
"""

[header]
image = "sensor/sensor.jpg"
caption = "Input test"

+++
In the final project of Principles of artificial intelligence, we managed to establish a neural network using tensorflow , tflearn and sklearn. We wrote our own JS collecting program and then analyzed the wave of motion sensors of smartphones and defined an touching event. Better than previous study deducing only 4-digit PIN, our model can give coordinates of the touching location on the phone screen and successfully recognized a sentence.

In the GIF below, we used the output coordinates of neural network as input to click the keyboard, only one letter(x->c) was wrong but with auto-correction we succeeded in re-creating the sentence: A secret!

![GIF](/img/sensor/sensor.gif)

For more information, please browse our {{% staticref "sensor/sensor.pdf" %}}slides(English){{% /staticref %}} and {{% staticref "sensor/sensor_report.pdf" %}}report(Chinese){{% /staticref %}}.
