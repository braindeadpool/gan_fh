# gan_fh
My experiments with GANs
------------------------

All models suffixed with `_fh` are compatible with floydhub environments.
For example, to run the MNIST GAN model in mnist_gan_fh.py, use command `floyd run --gpu --env tensorflow-1.0 "python gan_fh.py --mode train --batch_size 256 --num_epoch 60 --output_dir=/output/ --save_interval=100"`
