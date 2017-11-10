* mtrix dot product
* Single-layer Neural Network for Classification Problem
	1. 결과값을 0 or 1로 맞춰야함
		- Sigmoid(x) = 1 / (1 + e^(-x))
		- http://www.wolframalpha.com
	2. Sigmoid에 log를 씌운다. (loss function에서)
	3. 새로운 loss function을 정의한다.

	* loss func의 특징
		1. 미분 가능
		2. 0이면 좋음 무한대면 안좋음
		3. 복잡해도 상관 없다. 미분한게 깔끔하면 된다.
	* log 미분
		1. log x 를 x에 대해서 미분
		2. log f(x) 를 x에 대해서 미분