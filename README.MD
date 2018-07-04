# Variational Autoencoder

This is an replication, using the PyTorch framework, of the variational autoencoder neural networks described in Kingma and Welling 2013.
It is CUDA accelerated and should train very quickly on the appropriate hardware.

I have attempted to be true, where possible, to the original parameters and techniques of the paper.
Small implementation tweaks and parameter changes (beyond the parameters specified in the paper) can affect speed of training significantly,
but the results generally follow those of the paper.

The MCMC component of this project remains to be debugged and tweaked. I plan to return to it when I have better training hardware.
However, Kingma and Welling's paper does not specify many parameters of the MCMC procedures used, nor of the MCEM algorithm's particulars,
so I do not expect to closely replicate the results of those sections of the paper.
