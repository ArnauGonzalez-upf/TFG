# TFG

## About the files
Both applications have been developed in Python using Notebooks, which offer compatibility for different operative systems and can be used in Anaconda and Google Colab environments, which come with all the packages needed already installed so, for the users, it is a matter of downloading and executing them immediately. 

## What is each file?
IID.ipynb: Corresponds to the application to compute all the different equations and bounds derived in this thesis for the i.i.d. case.
CC.ipynb: The same as the last one but for the cost-constrained case.
DerivativesDemonstrationIID.ipynb This notebook demonstrates the relations between the derivatives of $E_0(\rho)$ and $\kappa_s(\rho)|_{s=\frac{1}{1+\rho}}$.
DerivativesDemonstrationIID.ipynb: The same as the last one but for the derivatives of $E_0(\rho, r)$ and $\kappa_{s,r}(\rho)|_{s=\frac{1}{1+\rho}}$.

\section{Configuration }
Before defining how the applications solve every problem and equation, we are going to define what can they do as well as everything that users can configure to do the calculations for their studies. So, we have the following sections:
\begin{itemize}
    \item \textbf{Mode:} There is only one parameter in this section and corresponds to which type of calculation will be done, where the options are: over $n$, $R$, or the SNR.
    \item \textbf{Constellation:} Since both applications are programmed to work with $M$-PAM modulations, users can select the length $M$ of the modulation to be generated.
    \item \textbf{Values of $n$:} Corresponds to the length $n$ of the sequence, and for the over $n$ mode a range of values from one to the selected value is generated. Users can select the number of generated values.
    \item \textbf{Rate:} In this section the rate $R$ for the calculations is set. For the over $R$ mode, a range of values from $0.01$ to the selected value is generated. To speed up computations the number of generated values to do the calculations can also be set.
    \item \textbf{SNR:} This section allows the users to select the mean energy per symbol $\E$ as well as the $\sigma$ values for the noise. For the latter, there are two options: for the modes in which the bounds are calculated over $n$ or $R$, only one value of $\sigma$ is needed; but for the mode in which are calculated over the SNR, users must select the $\sigma^2$ values at the beginning and the end of the range, being, in this case, squared to make an easier comparison to the SNR, but later are converted automatically to $\sigma$ using their square root.
    \item \textbf{Logarithmic view:} Toggle to set the $y$ axis in the plot results in a logarithmic scale.
    \item \textbf{Save data:} Another toggle, which in this case allows the user to save the results obtained.
\end{itemize}
