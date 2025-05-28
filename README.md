We want to sharpen an image, Create a kernel that highlights the target pixel. Then apply it to the image using filter2D, Sharpening works similarly to blurring, except instead of using a kernel to average the neighboring
values, we constructed a kernel to highlight the pixel itself. The resulting effect makes contrasts in
edges stand out more in the image
