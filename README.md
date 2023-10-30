# EMDSQA_test_corpus
We created a test corpus for speech quality assessment using speaker embeddings. This corpus has two goals:
1. Aim at the speech via online communication applications such as Zoom, Skype, Google Meet, Discord, etc. So the degradation types are typical communication distortions, which contain background noise (20%), packet loss (20%), non-linear processing (20%), and low-volume (20%).
2. Aim at the speech quality assessment using speaker embeddings. Both the matched reference and non-matched reference are provided for the degradation speech (i.e. non-matched reference stands for the reference speech is different from the degradation speech but from the same person).

Details: EMDSQA test corpus contains 120 wavs, the language is Mandarin, male:female is 1:1, and the sampling rate is 48kHz.

Speech: The original clean speech is from [1], and the degradations are processed by Zoom, Tencent Meeting, and Dingtalk.

Subjective Evaluation: Subjective evaluations are completed with 12 audio experts following the ITU-T P.808 [2] and ITU-R BS.1534 (MUSHRA) [3].

The MOS distributions are shown in the following figure.
![alt text](https://github.com/SherlockHao/EMDSQA_test_corpus/blob/main/MOS_EMDSQA.png)


