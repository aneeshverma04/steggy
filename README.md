# steggy
An image steganography encoder and decoder using LSB algorithm

Created in python 3.9.<br/>
Just use python app.py to run.

Enter input string to encode in ./resources/input.txt.<br/>
Default image used to hide data is ./resources/mangekyo.jpg which is of 3750x5000 pixels meaning it can store around 7 million characters.

Encoded image is stored in ./output/<br/>
Decoded text of the image is stored in ./output/

LSB algorithm(Least Significant Bit)<br/>
Only last bit is used of all R,G,B pixels

Encoding is done utf-8, so input outside of utf-8 will be ignored.

Verified for huge bulk of data.

Contact if any issues. In the next version, I will add some GUI to it.
