# Multilingual-Hate-Speech-and-Offensive-Language-Detection-of-Low-Resource-Languages

![Game Classifier and Recommender](hate-speech-detection-using-machine-learning.png)

The last decade has seen a steep rise in the use and dependence of society on social media. The need for detection and prevention of hate and offensive speech is more than ever. The everchanging form of natural language makes the detection of hate speech challenging, involving code-mixed text. The task becomes even more daunting in a country like India, where different languages and dialects are spoken across the country. This paper details the Code Fellas team's approaches in the context of HASOC 2023 - Task 4: Annihilate Hate, an initiative aimed at extending hate speech detection to Bengali, Bodo, and Assamese languages. Here we describe our approaches which broadly involve Long Short Term Memory (LSTM) coupled with Convolutional Neural Networks (CNN) and pre-trained Bidirectional Encoder Representations from Transformers (BERT) based models like IndicBERT {kakwani2020indicnlpsuite} and MuRIL {das2022data}. Notably, our results showcase the effectiveness of these approaches, with IndicBERT achieving a remarkable F1 score of 69.726\% for Assamese, MuRIL achieving 71.955\% for Bengali, and a BiLSTM model enhanced with an additional Dense Layer attaining an impressive 83.513\% for Bodo.

Due to privacy issues, we have not added the datasets in this repository. However, you can find the work we have done during the time of the competition.

## Features

- **Text Classification:** 
🚀 Unleash the Power of Our Models! Trained on an extensive dataset of **4036** Assamese texts, **1281** Bengali Texts and **1679** Bodo texts. It swiftly detects if text is offensive or not. Just drop the tweet, and let our models do the rest! 💡

- **Preprocessing Techniques:** Handled Usernames, URLs and newline characters. Elongated words have been reduced to their normal form. Converting text to tensors by tokenization to the tweets and padding the sequences accordingly.

- **BERT Models:** The backbone of our classification models are the pre-trained BERT models. Notably, our results showcase the effectiveness of these approaches, with **IndicBERT** achieving a remarkable F1 score of **69.726\%** for Assamese, **MuRIL** achieving **71.955\%** for Bengali, and a **BiLSTM** model enhanced with an additional Dense Layer attaining an impressive **83.513\%** for Bodo.

## How to Use

1. Clone this repository to your local machine.
2. Install the modules required using pip command.
3. Get access to the data from the [HASOC 2023 Team](https://hasocfire.github.io/hasoc/2023/dataset.html).
4. Run the file along with their respective datasets to get the desired output.

## Contributing

We welcome contributions from the community to improve our Hate Speech Detection. If you have any ideas, bug fixes, or additional features, feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

---

If you have any questions or need assistance, please don't hesitate to contact us. Happy coding!

**Author:** Abhinav Reddy Gutha, Nidamanuri Sai Adarsh, Ananya Alekar, Dinesh Reddy  
**Contact:** abhinavreddygutha@gmail.com, nidamanuri.adarsh.21031@iitgoa.ac.in, ananya.alekar.21031@iitgoa.ac.in, dinesh.reddy.21063@iitgoa.ac.in 
