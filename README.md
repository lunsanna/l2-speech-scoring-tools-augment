# l2-speech-scoring-tools-augment

This project extends the automatic speech rating systems by adding data augmentation pipelines. The system rates the proficiency levels of second language (L2) learners of Finnish and Finland Swedish automatically, given their spoken response to speaking tasks. 

The project aims to explore and compare different augmentation techniques. 

The ASR systems were trained by running 
- `run_asr_SLT_kfold.py` trains the ASR systems
- `extract_static_w2v2_features.py` extraxts hidden wav2vec 2.0 representations
- `run_classification_SLT_kfold.py` train speech rating wav2vec 2.0 systems
- `speech_rating_FI.ipynb` and `speech_rating_SV.ipynb` contain results of speech rating experiments for L2 Finnish and Finland Swedish
