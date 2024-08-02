# Web_dataset
웹페이지 분석을 위한 딥러닝 모델 학습과 구현에 관한 연구 논문에 사용된 데이터셋 모음

## /root/step1_SectionDetect
**(step1 학습 데이터)**

## /root/step2_HeaderClassification
**(step2 Header 학습데이터)**

## /root/step2_SectionClassification_for_detect
**(step2 TagCode 학습데이터)**

## /root/step3_SwiperDetect
**(step3 swiper 학습데이터)**

## /root/step3_ElementDetect
**(step3 Element 학습데이터)**

## /root/step3_Image_background_classification
**(step3 imageBackground 학습데이터)**

## /root/step3_OCRDATA
**(step3 OCR 데이터)**

## Data Image Label 현황


```
./
├─step1_SectionDectect
│  ├─train
│  │  ├─images
│  │  └─labels
│  └─valid
│      ├─images
│      └─labels
├─step2_HeaderClassification
│  └─header
│      ├─logo_center
│      └─logo_left
├─step2_SectionClassification_for_detect
│  ├─train
│  │  ├─images
│  │  └─labels
│  └─val
│      ├─images
│      └─labels
├─step3_ElementDetect
│  ├─train
│  │  ├─images
│  │  └─labels
│  └─val
│      ├─images
│      └─labels
├─step3_Image_background_Classification
│  ├─notnuggi
│  └─remove_bg
├─step3_OCRDATA
└─step3_swiperDetect
    ├─train
    │  ├─images
    │  └─labels
    └─val
        ├─images
        └─labels
```

EX_Img안에는 학습 시 실제 레이블이 어떻게 쳐져있는지에 대한, 이미지 참고용 자료입니다.

각 폴더 안에는 실제 학습에 사용된 자료 전체 혹은 일부가 첨부 되어있습니다.

Git Hub에 업로드를 위해 .z* 파일로 분할압축을 하였습니다. Web_dataset.zip 번을 클릭해서 압축해제하시면 됩니다.

전체 git을 Clone 받아 압축 해제 후 원하시는 데이터를 확인하시면 될 것 같습니다.
