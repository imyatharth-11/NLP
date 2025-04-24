1. Gen_Embeddings file is used to create embeddings for the resume text that is parsed using the transformer encoder. The embeddings created are saved in a pickle file.
2. Embeddings_Combiner is used to combine the embeddings that are created and save one single pickle file for the embeddings.
3. Train_Test_Save_Model is used for training, testing and saving the model
4. Gradio_Final is where you'll upload the resume which will extract the required skillset, due the pre-processing like lemmatization, generate embeddings for the extracted text and send it to the model to check the similarity with the job description.
