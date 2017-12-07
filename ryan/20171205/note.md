- Small Random Number
	- 뉴런의 개수가 늘어날 수로 세츄레이션될 확률이 높아진다.
	- fan in / fan out
	- 좋은 weight initializer는
		- 모든 activation func에 범용적으로 적용할 수 있어야함
		- layer 사이에 다음 레이어에 넣는 값이 일정했으면...
		- 평균이 0이었으면 좋겠다
	- fan in의 평균, 분산과 fan out의 평균, 분산의 값이 같은 weight를 초기화하고싶다.

- Model Evaluation
	- 모델을 검증하는 방법

	- Live Evaluation
	- Offline Evaluation
		- Hold Out Validation -> 전체 데이터를 일부는 트레인, 일부는 테스트로 나눈다.
		- Cross Validation

	- Classification Metrics
		- Accuracy (정확도 퍼센트)
		- Confusion Matrix
		- Per Class Accuracy
		- Log Loss -> 크로스 엔트로피
	- Regression
		- Mean Absolute Error
		- Mean Squared Error
		- 