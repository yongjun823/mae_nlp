# mae_nlp

## 준비사항
* [csv file link](https://drive.google.com/open?id=1umHwE6fje9dN9N2DqqGawR8Z-X-cQHav)
* 라이브러리 설치 
* [gensim pretrain model link](https://github.com/jhlau/doc2vec)
* gensim 모델에서 word2vec과 doc2vec 학습 모델 다운로드

``` sh
pip install requirements.txt
```

## 디렉토리 구조 
```
├── mae_data
│   ├── csv
│   │   ├── fashion_img.csv
│   │   ├── img_label1.csv
│   │   ├── mae_data.csv
│   │   ├── mae_img0_9.csv
│   │   ├── mae_img10_16.csv
│   │   └── mae_img_label.csv
│   ├── gensim_model
│   │   └── apnews_dbow
│   │       ├── doc2vec.bin
│   │       ├── doc2vec.bin.syn0.npy
│   │       └── doc2vec.bin.syn1neg.npy
│   ├── kr (json 파일들)
│   ├── train (json 파일들)
│   └── val (json 파일들)
```

## [image ai label 분석](https://github.com/yongjun823/mae_nlp/blob/master/image%20ai%20label%20word2vec.ipynb)

## [mae title](https://github.com/yongjun823/mae_nlp/blob/master/mae_title.ipynb)

## [nltk gensim ibm](https://github.com/yongjun823/mae_nlp/blob/master/nltk%20test%20wor2vec%20doc2vec%20IBM%20API.ipynb)



