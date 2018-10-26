# LUKS-guided-manual-partitioning
Easily install Ubuntu with FDE and semi-manual partitioning see the full write-up [here](https://adventures-in-tech.blogspot.com/2018/10/encrypted-ubuntu-installation-with.html)

In short, LGMP enables you to set up an encrypted Ubuntu installation with semi-manual partitioning. In fact, if you know what you're doing, you could very easily set up additional logical volumes during the installation process.
In addition, LGMP creates some useful scripts on the desktop that can be used to change the encryption passphrase or recover from a forgotten passphrase, recover from corrupted LUKS headers, and reinstall to the same encrypted setup, keeping /home intact.
