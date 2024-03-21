# MSTAR-ASC-Data-Set

This is an parameter estimation result data set of the Attributed Scattering Center (ASC).
The original Data set is the MSTAR data set, we convert MSTAR 1 to the frequency domain and extract the ASC from more than 7000+ SAR image chips.


The MSTAR-ASC dataset is available at:
- Baidu Netdisk: https://pan.baidu.com/s/1zSKz9HoQpAX5l2cbvICfQw?pwd=xu95 CODE:xu95
- Google Netdisk: coming soon

The original MSTAR dataset can be download at:
- https://pan.baidu.com/s/18fYZ1r7qUTHZ7HnGku1HYQ?pwd=x81l CODE:x81l
- https://www.sdms.afrl.af.mil/index.php?collection=mstar [official url]



## Estimation algorithm and code
The algorithm including `OMP` using alternative optimization, and the improved algorithm named `SOMP`.

We will release the code of the ordinary [OMP](https://github.com/LongboV/OMP-SOMP-Code-for-MSTAR-ASC) method firstly.
And we will release the code of the improved `SOMP` after the paper being published. 

**IMPORTANT!** The OMP code is realised by myself and is not the official version of the original authors 2.

## Data set readme
Please see the home page of the MSTAR-ASC dataset， there is a README.pdf
Next step, We will release more code for using the data set.


## Reference
- 1 https://www.sdms.afrl.af.mil/index.php?collection=mstar
- 2 H. Liu, B. Jiu, F. Li and Y. Wang, "Attributed Scattering Center Extraction Algorithm Based on Sparse Representation With Dictionary Refinement, " in IEEE Transactions on Antennas and Propagation, vol. 65, no. 5, pp. 2604-2614, May 2017
