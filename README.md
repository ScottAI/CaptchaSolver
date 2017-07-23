# CaptchaSolver
## Summary
Simple scripts for captcha cracking with convolution neural network via TensorFlow.

Aimed at the six-digit captcha from [Russian federal migration service](http://services.fms.gov.ru/info-service.htm?sid=2000).

Accuracy for single digit is about 95%
## Requirements (Python packages)
* `tensorflow >= 0.12.1`
* `Pillow >= 4.2.1`
## Data
There are training and test data samples in the archives:
* `data_train.tar.xz` contains 9.000 images
* `data_test.tar.xz` contains 450 images

Both samples contains marked images, so you can easily change proportion between them.
## How to launch scripts
* Unpack both archives
* `python single_digit.py` - run with the network for recognizing single digit
* `python all_digits.py` - run with the network for recognizing whole captcha
