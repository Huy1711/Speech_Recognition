# Speech_Recognition

Speech Recognition using DTW and HMM

Name: Nguyen Duc Huy

Student ID: 19021299

Video demo: [Youtube video](https://youtu.be/8ffKuPzhMJI)

Google Colab Notebook: [Colab Notebook](https://colab.research.google.com/drive/1Gb_EwjZoRqIEEY8pgPzbLUdbr-ynox2H?usp=sharing)

labels = {A, B, len, xuong, phai, trai, nhay, ban, sil}

Requirement packages:
```
pip install pydub
pip install librosa
pip install hmmlearn
```
Task list
- [x] Extract mfccs from .wav files and save to .txt file
- [x] DTW using multiple template (Average templates)
- [x] GMMHMM