<h1>Encoder/Decoder implementation for AWGN Channel Communication</h1>


<h2>Description</h2>

This is an implementation of an encoder/decoder pair that uses a 64-QAM constellation to communicate a fixed-length ASCII string of 78 characters over an Additive White Gaussian Noise (AWGN) channel. The system has been designed to operate under specific constraints, including minimum error rate and energy and size limitations.

The encoding process involves mapping each chunk of bits to a specific point in the 64-QAM constellation, which is then transmitted over the AWGN channel. The decoding process involves finding the closest point in the constellation to the received symbol and mapping it back to its corresponding chunk of bits. The system uses various criterion functions to determine the best mapping, including a minimum distance criterion.

The 64-QAM constellation used is generated using the m-QAM technique, where m is a power of 2. You can find a function that generates the entire constellation for any value of m, as well as handling various special cases for specific values of m, such as 2 and 8.

<h2>Languages Used</h2>

- <b>Python </b> 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
