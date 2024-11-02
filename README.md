# 해양 쓰레기 탐지 프로젝트 (Marine Litter Detection Project)
이 프로젝트는 YOLOv5 모델을 사용하여 해양 쓰레기를 검출하고 분석하는 것을 목적으로 합니다. 

## 디렉토리 설명
- **Pre-processing**: .xml 확장자로 이루어진 라벨링 데이터를 .txt 확장자로 변경
- **Colab_train**: 커스텀 yaml 파일 생성 및 yolov5 학습 및 검출

## 클래스
``` python
class_mapping = {
    "tire": 0,
    "spring fish trap": 1,
    "circular fish trap": 2,
    "rectangular fish trap": 3,
    "eel fish trap": 4,
    "fish net": 5,
    "wood": 6,
    "rope": 7,
    "bundle of ropes": 8
}
```

## 데이터셋
- AI-Hub: https://aihub.or.kr/aihubdata/data/view.do?dataSetSn=236

## 코랩 링크:
- https://colab.research.google.com/drive/1cSU17fzt862Amh0ROn-iDXTEkG1Z-HCD?usp=sharing

## 출처
- YOLOv5 Tutorial: https://colab.research.google.com/github/ultralytics/yolov5/blob/master/tutorial.ipynb#scrollTo=zR9ZbuQCH7FX
- YOLOv5 커스텀 데이터셋 학습: https://blog.taehun.dev/training-yolov5