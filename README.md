The following demonstration is shared purely to pique your curiosity—please do not feel obligated to achieve the performance shown here. It showcases a heavily optimized solution operating near the practical limits of what's possible. We strongly recommend focusing first on the tasks and suggestions outlined in the M3 document to maximize your grade.

Here's the demo. You can reach around 165 FPS in quad mode

<p align="center">
    <video autoplay loop width="640">
    <source src="videos/quad_greyscale.mp4" type="video/mp4">
    Your browser does not support the video tag.
    </video>
</p>

This means that reading from SPI, processing, and updating the pixel buffer all complete in roughly 6 ms per frame. The "cam FPS" refers to the native refresh rate of the ESP32-CAM—i.e., the interval between `cam_ready` PIN assertions. You can also reach 13.8 FPS with full RGB image + processing.

<p align="center">
    <video autoplay loop width="640">
    <source src="videos/full_RGB.mp4" type="video/mp4">
    Your browser does not support the video tag.
    </video>
</p>

**PLEASE NOTE**: While attempting this level of performance won't do much for your grade, pulling it off will definitely earn you a few

<p align="center">
    <img src="https://i.giphy.com/NEvPzZ8bd1V4Y.webp" />
</p>

from the teaching staff!