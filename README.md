# Basic Usage
To train with default parameters on the tinyshakespeare corpus, run:
```bash
python train.py
```

To sample from a trained model
```bash
python sample.py
```

To pick using beam search, use the `--pick` parameter. Beam search can be
further customized using the `--width` parameter, which sets the number of beams
to search with. For example:
```bash
python sample.py --pick 2 --width 4
```

# Information

This is a fun project to study and train an IA based on someones Tweet history, it doesn't have much into it other than some few tries but it worked very well.

# Requirements

It is required to have Python version 3.7.x and TensorFlow version 1.15.
You will also need an virtual enviroment to install the TensorFlow.
Docs that are useful:
https://www.tensorflow.org/install/pip#virtual-environment-install
https://martinfritz.medium.com/work-with-multiple-versions-of-python-on-windows-10-eed1e5f52f07#:~:text=Install%20multiple%20python%20versions&text=For%20Windows%20users%2C%20I%20recommend,the%20Windows%20x86%20executable%20installer%20.&text=After%20locating%20the%20install%20option,just%20press%20the%20download%20link.


# AI/Credits

Mostly reused code from an existing repository: https://github.com/hunkim/word-rnn-tensorflow
