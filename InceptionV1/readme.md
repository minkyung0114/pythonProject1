# InceptionV1 논문리뷰 

"Going deeper with convolution"


### InceptionV1 

#### 배경
- layer를 깊게 쌓을 수록 파라미터가 증가하여 overfiting이 발생할 가능성이 높아짐 
- 즉, 계산 복잡도가 증가함
- overfitting이 발생하게되면 새로운 test데이터가 났을 때, 반응을 잘못함 

  
#### Inception 구조 
- layer가 깊어질수록 gradient vanishing이 발생하여 중간중간에 softmax를 뽑아냄 

![inceptionV1구조](https://user-images.githubusercontent.com/70430385/161255623-e18eacfd-9922-44d0-b907-852b6b4aa7a2.png)


#### Inception 모듈  
- 병렬로 pooling
- 연산량 때문에 1x1 cov사용 


#### Reference
https://arxiv.org/pdf/1409.4842.pdf
