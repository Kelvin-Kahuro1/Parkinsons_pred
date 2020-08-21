# Parkinsons Disease Prediction
The notebook contains code illustrating of parkinsons disease prediction using xgboost classifier algorithm.

The dataset used in the prediction was created by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, 
Colorado, who recorded the speech signals. The original study published the feature extraction methods for general voice disorders.

Attribute Information:
Matrix column entries (attributes):
1. name - ASCII subject name and recording number
2. MDVP:Fo(Hz) - Average vocal fundamental frequency
3. MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
4. MDVP:Flo(Hz) - Minimum vocal fundamental frequency
5. MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several 
6. measures of variation in fundamental frequency
7. MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
8. NHR,HNR - Two measures of ratio of noise to tonal components in the voice
9. Status - Health status of the subject (one) - Parkinson's, (zero) - healthy
10.RPDE,D2 - Two nonlinear dynamical complexity measures
11.DFA - Signal fractal scaling exponent
12.Spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

Paper citation:
1. 'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection',Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. 
    BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)
