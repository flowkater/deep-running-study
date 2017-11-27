* Dataset

  * 인터넷에 공개되어 있는 데이터 (연습용)
    * Kaggle
    * MNIST
    * CIFAR-10
    * PASCAL VOC
  * 실제로 쓸만한 데이터
    * ImageNet (image-net.org)
    * COCO
  * 그럼에도 불구하고 데이터를 저기하려면?
    * Mechanical Turk
    * B2B

* 1X1 convolutional layer

  * 차원 축소
  * Fully-connected layer를 대체할 수 있다. (Multi-layer 부분)
  * Fully-connected layer는 Input 사이즈에 민감

  # Activation function

  * 튜닝
    * Hyperparameter Optimization
    * Weight Initialization
    * Convolutional Layer
    * Activation Function
    * Automatic Differentiation
    * Optimizer
  * Sigmoid 함수 단점
    * Saturation 현상
    * 결과 값이 오직 0~1 사이로만 나온다
    * exp 연산이 굉장히 느리다
  * 해결책
    * hyperbolic tangent
      * 결과값이 -1 ~ 1 사이
      * 변함없이 Saturation 현상 발생
    * ReLU (rectified linear unit)
      * f(x) = max(0, x)
      * zigzag할 수 있음
      * 변함없이 Saturation 현상 발생할 수 있음
      * 해결책
    * Leacky ReLU
    * Parametric ReLU
    * ELU (Exponentioal Linear Unit)
    * SReLU (S-shaped rectified linear activation unit)
      * 나온지 얼마되지 않음. 검증되지 않은 느낌적인 느낌
    * Maxout
    * ​