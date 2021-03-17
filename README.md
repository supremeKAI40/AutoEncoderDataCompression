# AutoEncoderDataCompression
Following is an experiment with particle physics data obtained from LHC events using its state-of-the-art detectors. I aim to compress the data obtained from such events from its 4-Dimentional(Energy and 3 momentum components) data to 3-Dimensional. 

<br>I used 7 layer Deep Neural Network Encoder with TanH Activation Function to compress the data from 4D to 3D. Complete Layer Structure would be "in-200-200-20-3-20-200-200-out" where ideally in and out should be same. 
<br>
The middle layer is the compressed data which can then be further handled. Since every encoder has to have a decoder to again make the data physiclly interpratable, thus the symmatric nature of the complete Network.

<br> The following project is built upon the work by <a href="https://github.com/erwulff">Eric Wulff</a> and Honey Gupta with Dataset provided by the CERN mentors. 
