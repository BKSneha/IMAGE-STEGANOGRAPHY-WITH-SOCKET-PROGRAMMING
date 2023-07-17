# IMAGE-STEGANOGRAPHY-WITH-SOCKET-PROGRAMMING
In this proposed system, we deal with least significant method of image steganography that
hides the secret message in the least significant bits of the pixel values without introducing
many perceptible distortions and using socket programming to transmit the steganographic image between networked computers.
The sender program reads a cover image and a secret text, performs steganography by replacing the least significant bits of the cover image pixels with the secret text, and saves the resulting steganographic image. It establishes a socket connection with the receiver program and sends the steganographic image over the network.

The receiver program establishes a socket connection, accepts the incoming connection from the sender program, receives the steganographic image, and saves it. It can then perform decoding to extract the hidden secret information from the received steganographic image.
Overall it performs steganography on an image, embedding secret information, and then uses socket programming to transmit the steganographic image to another computer over the network.
