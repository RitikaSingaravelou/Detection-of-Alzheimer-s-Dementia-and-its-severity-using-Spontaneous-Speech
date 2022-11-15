# Detection-of-Alzheimer-s-Dementia-and-its-severity-using-Spontaneous-Speech

Alzheimer’s Disease (AD) is a degenerative brain disorder that affects millions of people
around the world. AD is also the most predominant form of dementia that affects memory,
cognition, motor skills and linguistic abilities of patients. Since there is no cure for this disease
at present, it is imperative to diagnose AD at its earliest stages in order to provide appropriate
care to hinder its progression and prevent it from affecting the patient’s overall quality of life.
Popular methods used for screening AD like functional and structural Magnetic Resonance
Imaging (MRI), Positron Emission Tomography (PET) images, Electroencephalogram (EEG)
signals and Cerebrospinal Fluid (CSF) exams are expensive, highly invasive and inaccessible
to several sections of society. Careful analysis of various symptoms of AD reveals that speech
and language impairments act as an effective means for early detection. Patients often struggle
with names of common objects, formation of meaningful sentences, and lack coherence and
clarity while speaking. In this work, spontaneous speech is utilized to obtain audio and
transcripts and extract useful acoustic and linguistic features from them. Models for the two
modalities, audio and text, are trained separately and the most efficient feature combinations
are selected. These are fused at the feature level (early multimodal fusion) and used for
classifying people into AD and non-AD groups. The level of severity is also predicted by
carrying out the Mini Mental State Examination (MMSE) score prediction task using the fused
features. Early fusion of acoustic and linguistic features used in this work helps in detecting
AD with an accuracy of 81.2% and also determine severity of the disease by predicting the
MMSE Score with a root mean square error of 4.703.

ADReSS Challenge - https://luzs.gitlab.io/adress/
