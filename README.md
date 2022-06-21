# Amharic Sentiment Analysis - Hate Speech Detection Using Machine Learning

The scope of this project is limited to the presence or absence of hate 
speech on Amharic language Twitter posts. In this context, the term 'hate speech' 
refers to abusive or threatening statements or phrases that describe prejudice against 
a particular group in Ethiopia.


## Advisor

- Elefelious Getachew (Ph.D.)


## Members

- [Surafel Kindu](https://github.com/Surafeljava) - ATR/9237/10 - Section-1
- [Samia Abdella](https://github.com/Surafeljava) - ATR/3142/10 - Section-1
- [Daniel Tefera](https://github.com/Surafeljava) - ATR/1145/10 - Section-1
- [Eyob Maru](https://github.com/Surafeljava) - ATR/0121/10 - Section-1
- [Ahlam Muhdin](https://github.com/Surafeljava) - ATR/2923/10 - Section-3

## How to run model training locally

To run the trainings first begin by cloning the [This Repository](https://github.com/Surafeljava/asa-training)

### Requirements on users machine before running the project

The training code is made with python using tensorflow and keras:

* Download and install python locally on your computer: [Nodejs Download Link](https://www.python.org/downloads/)

After installing python you can go a head and run the following command on the project folder directory

* Install All Packages

```bash
  pip install tensorflow numpy transformers pytorch-lightning
```

* Run the trainings by locating to the individual files inside LM and Sentiment Training folders

```bash
  python AmBERT.ipynb
```

```bash
  python asa_hate_classifier.ipynb
```

This training will need big data sets which can't not be placed on github due to file size limitations therefore we put them on google drive with publicy available link below

- [Sentiment Training Data](https://drive.google.com/file/d/1HtCquADZQl0WxKEnlWoS0-j5kORU5QjL/view?usp=sharing)
- [Sentiment Validation Data](https://drive.google.com/file/d/1scM0dxX5dSFnipDENhUQB-Glv_4SI7mz/view?usp=sharing)

- [Amharic Corpus (For Language Model Training)](https://drive.google.com/file/d/1eQ5wjUvqwpg63SlfdltDK76Bgiaa3rrg/view?usp=sharing)

### Run and test from Google Colab

The project is made with Google Colab and we have attached the link below for further test

[AmBERT (our Amharic Language Model)](https://colab.research.google.com/drive/1oOoVFRzjXiFFoqR3ZhTkI-f2OlU9Dza_?usp=sharing)

[Amharic Sentiment Classifier](https://colab.research.google.com/drive/1oOoVFRzjXiFFoqR3ZhTkI-f2OlU9Dza_?usp=sharing)

## References and Documentations used while developing this project

* [RoBERTa Transformer](https://huggingface.co/docs/transformers/model_doc/roberta)
* [How to use transformers](https://www.youtube.com/watch?v=LE3NfEULV6k&t=1171s)
* [Finetuning with transformers](https://www.youtube.com/watch?v=GSt00_-0ncQ&t=552s)
