# Segmentation using UNet
Our dataset of 25 images labeled for rooftop segmentation suffers from limitations due to its size. While the results are usable, a larger dataset would likely improve accuracy. Additionally, the labels currently use a range of values between 0 and 255 instead of a binary format (0 or 255). To facilitate processing, we will convert these labels to a binary format, acknowledging that this may introduce minor label deformations. We welcome suggestions for alternative solutions.

The final version is in the final_code.ipynb
https://github.com/fereshteh-bahadory/Segmentation-for-rooftop-images/blob/main/final_code.ipynb

