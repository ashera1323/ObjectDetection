# ObjectDetection

This is computer vision project aimed to train models Yolo8 and Detectron2 to detect Fir-tree and Yandex rovers on pictures.
In the proccess, after processing all steps and evaluation: Detectron2 model achived more accurate results.

Models used: Yolov8 and Detectron2.

More about models itself you can read on: https://roboflow.com/model/yolov8 and https://roboflow.com/model/detectron2.

Dataset: consists of 104 pictures: Fir-trees and Yandex rovers. Picture size: 6000 x 4000. Resolution: 72 x 72

Dataset itself: https://app.roboflow.com/appliedml/objdetection-uu4zf/1

#### Step 1: Dataset Collection.
Dataset was colected manually: 100+ photos of fir-tree and yandex rovers was taken.
#### Step 2: Annotation labels on object using roboflow <img width="1267" alt="Снимок экрана 2023-03-06 в 23 10 24" src="https://user-images.githubusercontent.com/80173158/223219659-b33ba18f-905f-4a84-8731-4f30b2f2428c.png">
#### Step 3: After data preperation, we push our dataset to detectron2 model: fit and train it.![photo_2023-03-06 23 13 35](https://user-images.githubusercontent.com/80173158/223220304-7dab4504-88d8-4c75-a492-18d91eea593e.jpeg)

link to colab: https://colab.research.google.com/drive/1jStZF5V6c29QKw6Bz8EZudsxphBx0VHX?usp=sharing

### Step 4: Train Yolov8 in the same manner.

link to colab: https://colab.research.google.com/drive/1BKI7C5Ug7SVN9WJnOpFmfq-TQGeZwyDJ?usp=sharing

### Step 5: Evaluation. 
Yolov8: 
<img width="1041" alt="Снимок экрана 2023-03-06 в 23 16 01" src="https://user-images.githubusercontent.com/80173158/223220786-8ae4ed93-c95c-42f2-88c8-be53e8e7204b.png">
detectron2:
<img width="910" alt="Снимок экрана 2023-03-06 в 23 33 03" src="https://user-images.githubusercontent.com/80173158/223224145-a6ff579c-93e4-4198-9a81-c75823f7a29a.png">
