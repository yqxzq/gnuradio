The above three files are gnuradio flow charts for wireless transmission of pictures or videos using hcakrf.
The design idea of this flow chart is to read the data of pictures or videos into gnuradio, encode it with ldpc code, then add frame headers, and then transmit the data after qpsk modulation.
At the receiving end, qpsk demodulation is performed first, then the data frame header is extracted, and then ldpc decoding is performed.
