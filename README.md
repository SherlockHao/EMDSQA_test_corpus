# EMDSQA_test_corpus
We created a test corpus for speech quality assessment using speaker embeddings. This corpus has two goals:
1. Aim at the speech via online communication applications such as Zoom, Skype, Google Meet, Discord, etc. So the degradation types are typical communication distortions, which contain background noise (20%), packet loss (20%), non-linear processing (20%), and low-volume (20%).
2. Aim at the speech quality assessment using speaker embeddings. Both the matched reference and non-matched reference are provided for the degradation speech (i.e. non-matched reference stands for the reference speech is different from the degradation speech but from the same person).

Details: EMDSQA test corpus contains 120 wavs, the language is Mandarin, male:female is 1:1, and the sampling rate is 48kHz.<br />
Speech: The original clean speech is from [1], and the degradations are processed by Zoom, Tencent Meeting, and Dingtalk.<br />
Subjective Evaluation: Subjective evaluations are completed with 12 audio experts following the ITU-T P.808 [2] and ITU-R BS.1534 (MUSHRA) [3].<br />
The MOS distributions of EMDSQA test corpus are shown in the following figure.<br />
<img src="https://github.com/SherlockHao/EMDSQA_test_corpus/blob/main/MOS_EMDSQA.png" width=50% height=50%>

# NISQA_test_corpus
Besides EMDSQA test corpus, another 120 wavs are selected from NISQA corpus [4], the language is Engilish, and the sampling rate is 48kHz.<br />
The MOS distributions of NISQA test corpus are shown in the following figure.
<img src="https://github.com/SherlockHao/EMDSQA_test_corpus/blob/main/MOS_NISQA.png" width=50% height=50%>

# Reference:
[1] Reddy, Chandan KA, et al. "Interspeech 2021 deep noise suppression challenge." arXiv preprint arXiv:2101.01902 (2021).<br />
[2] Naderi, B., Cutler, R. "An Open Source Implementation of ITU- T Recommendation P.808 with Validation." in Interspeech, 2020, pp. 2862-2866.<br />
[3] Liebetrau, Judith, et al. "Revision of rec. ITU-R BS.1534." 137th AES convention 2014.<br />
[4] Mittag, G., Naderi, B., Chehadi, et al., "NISQA: A Deep CNN- Self-Attention Model for Multidimensional Speech Quality Prediction with Crowdsourced Datasets." in Interspeech, 2021, 2127-2131.


