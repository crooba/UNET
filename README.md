# UNET

UNET


세포막 세그맨테이션

세포막경계를 분할하는 UNET신경망코드입니다.대략 10번의 반복학습을 통해 96%정도의 정확도를 획득했습니다.
데이터구조는 깃허브에 올려진 데이터 구조대로 사용하시길 권장드립니다. 그리고 코드상의 데이터경로는 각자의 시스템상의 데이터경로로 업데이트 하셔야 합니다. 업데이트 할 데이터경로는 main.py 코드상의 train폴더와 test 폴더 경로입니다.


사용법

데이터셋과 코드를 다운로드하시고 main.py의 경로를 제지정하신 후 파일을 실행하시면 UNET 세그멘테이션 신경망이 훈련되고 결과물이 test폴더에 저장 됩니다.
아래 이미지는 세포현미경이미지(왼쪽)와 그것을 토대로 훈련받은 유넷신경망이 세그맨테이션 한 세포경계선이미지(오른쪽)입니다.
전문가들의 손작업을 기준으로 약96%의 정확도로 훈련되었습니다.



UNET


cell membrane segmentation

This is a UNET neural network code that divides the cell membrane boundary.We have achieved 96% accuracy through approximately 10 iterations.
We recommend that you use the data structure on the flaghub. And the data path on the code must be updated to the data path on your system. The data path to update is the trainfolder and test folder path on the main.py code.


directions for use

Download the dataset and code, block the path to main.py, and run the file to train the UNET Segmentation neural network and store the results in the testfolder.
The image below shows a cell microscopic image (left) and a network of unnet nerves trained based on it, the cell boundary image (right) of the segmentation.
It was trained with about 96% accuracy based on handwork by experts.


<img width="1280" alt="result" src="https://user-images.githubusercontent.com/45910733/74008116-721a5480-49c3-11ea-837b-597502834195.png">
