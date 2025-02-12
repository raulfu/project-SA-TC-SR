# project-SA-TS-SR

This is an NLP project to create a little interface able to make a summary and detect the emotions of an input that can be either a written text or a speech. Main_project_using_ASR notebook has this interface.

- (TS) Models from[HugginFace](https://huggingface.co/) are used for the text summarization task and text generation.
- (SA) To train the Sentiment Analysis model, the bert_large_uncased_goemotions dataset is used.
- (SR) For speech recognition, the Gradio model is used.

Note that all the data used for training is not in the repo, notebook Main_project_using_ASR can be executed with the data of the repo, but notebook "Raul_Sequence classification - sentiment analysis", which contains the training, should not be run.
