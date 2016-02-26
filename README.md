# Sumproduct
Sumproduct algorithm using in encoding and decoing 
There are two folders "BP" and "Min_Sum" for the two projects corresponding to the two algorithms.(BP is the MaxProduct ALG and Min_Sum is the Sumproduct ALG)
In each of the two folder, the given H matrix is written in the "mat.txt" in sparse form.

The projects each contains :

SumProduct.h 
Main_MaxProduct.cpp / Main_SumProduct.cpp
initi_MP.cpp / initi_Sum.cpp
transform.cpp
encode.cpp
channel.cpp
decode_MP.cpp / decode_Sum.cpp

The output files are:

Gaussian_exchange_cols.txt
P_MAT.txt
ber_BP.txt / ber_MinSum.txt

All source code files are in the "src" folder.

In the "Matlab" folder, the "SumProduct.m" is the executable matlab file that reads "ber_BP.txt" and "ber_MinSum.txt" and plot the SNR-BER curves.


