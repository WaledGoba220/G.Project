1 ==> 
In Frist Model Tuberculosis 
==> input parameter is image the user upload image(input) to detect
==> output is (Normal) or (Positive Tuberculosis) output(text)

=========================================================================================

2 ==> 
In Second Model Pneumonia 
==> input parameter is image the user upload image(input) to detect
==> output is (Normal) or (Positive Pneumonia) output(text)

=========================================================================================
3 ==> 
In Third Model Lungs Cancer 
==> Dataset is ==> 
 0   GENDER                 309 non-null    object  ==> not depend in model
 1   AGE                    309 non-null    int64 
 2   SMOKING                309 non-null    int64 
 3   YELLOW_FINGERS         309 non-null    int64 
 4   ANXIETY                309 non-null    int64 
 5   PEER_PRESSURE          309 non-null    int64 
 6   CHRONIC DISEASE        309 non-null    int64 
 7   FATIGUE                309 non-null    int64 
 8   ALLERGY                309 non-null    int64 
 9   WHEEZING               309 non-null    int64 
 10  ALCOHOL CONSUMING      309 non-null    int64 
 11  COUGHING               309 non-null    int64 
 12  SHORTNESS OF BREATH    309 non-null    int64 
 13  SWALLOWING DIFFICULTY  309 non-null    int64 
 14  CHEST PAIN             309 non-null    int64 
 15  LUNG_CANCER            309 non-null    object   ==> this output


detection depend all not(GENDER & LUNG_CANCER)
==> output is (Normal) or (Positive Cancer) output(text)

=========================================================================================
