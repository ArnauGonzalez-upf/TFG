# TFG

## About the files
Both applications have been developed in Python using Notebooks, which offer compatibility for different operative systems and can be used in Anaconda and Google Colab environments, which come with all the packages needed already installed so, for the users, it is a matter of downloading and executing them immediately. 

## What is each file?
IID.ipynb: Corresponds to the application to compute all the different equations and bounds derived in this thesis for the i.i.d. case.
CC.ipynb: The same as the last one but for the cost-constrained case.
DerivativesDemonstrationIID.ipynb This notebook demonstrates the relations between the derivatives for the i.i.d. case.
DerivativesDemonstrationIID.ipynb: The same as the last one but for the cost-constrained case derivatives.

## Configuration
So, we have the following configuration sections:

- **Mode:** There is only one parameter in this section and corresponds to which type of calculation will be done, where the options are: over $n$, $R$, or the SNR.
- **Constellation:** Since both applications are programmed to work with $M$-PAM modulations, users can select the length $M$ of the modulation to be generated.
- **Values of $n$:** Corresponds to the length $n$ of the sequence, and for the over $n$ mode a range of values from one to the selected value is generated. Users can select the number of generated values.
- **Rate:** In this section the rate $R$ for the calculations is set. For the over $R$ mode, a range of values from $0.01$ to the selected value is generated. To speed up computations the number of generated values to do the calculations can also be set.
- **SNR:** This section allows the users to select the mean energy per symbol E as well as the sigma values for the noise. For the latter, there are two options: for the modes in which the bounds are calculated over n or R, only one value of sigma is needed; but for the mode in which are calculated over the SNR, users must select the sigma^2 values at the beginning and the end of the range, being, in this case, squared to make an easier comparison to the SNR, but later are converted automatically to sigma using their square root.
- **Logarithmic view:** Toggle to set the $y$ axis in the plot results in a logarithmic scale.
- **Save data:** Another toggle, which in this case allows the user to save the results obtained.
