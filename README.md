This python script preforms an MFCC analysis of every .wav file in a specified directory and saves the filterbank
energies for each file in a new directory (as a .csv). MFCCs (Mel-frequency cepstral coefficients) are most commonly used as the input features for automatic speech recognition. 

For more info see: Davis, S. B., & Mermelstein, P. (1980). Comparison of parametric representations for monosyllabic word recognition in continuously spoken sentences. Acoustics, Speech and Signal Processing, IEEE Transactions on, 28(4), 357-366.

Please note: running this script multiple times will overwrite earlier analyses

Requires python_speech_features. Documentation: https://github.com/jameslyons/python_speech_features)

Requires scipy. Documentation: https://www.scipy.org/install.html

Script written by Rachael Tatman (rachael.tatman@gmail.com), supported by National Science Foundation grant DGE-1256082
