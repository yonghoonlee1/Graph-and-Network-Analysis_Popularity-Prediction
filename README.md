# Popularity Prediction

연세대학교 대학원 수업 Graph and Network Analysis 에서 진행된 Competition 프로젝트

인터넷의 웹 페이지는 하이퍼링크로 서로 연결이 되고
이는 각 웹 페이지가 네트워크의 Node, Node 쌍 사이가 Edge가 되는 네트워크로 표현할 수 있음

웹 페이지 방문자 수를 기준으로 인기도를 측정할 수 있는데,
다른 웹 페이지의 알려진 인기에 기초하여 일부 웹 페이지의 인기를 예측하는 프로젝트

* Dataset
  - 1000개의 노드
  - Class_info : 첫 번째 열은 노드 인덱스(1~1000), 두 번째 열은 각 노드의 클래스(-1: 비인기, +1: 인기, 0: 알 수 없음)
  - Edge_list : 방향과 가중치가 없는 Edge에 대한 두 노드의 인덱스가 포함

* Task : 클래스가 주어진 200개의 노드들로 학습 후, 인기도를 알 수 없는 800개 노드들의 인기도를 예측 (2개 중 하나 : 비인기 or 인기)

* Schedule
  - 2020.11.30 : 프로젝트 시작
  - 2020.12.18 23시 59분 : 제출 마감

* 활용 모델 : Node Embedding(Node2vec) + Convolutional Neural Networks

* 결과 : 8등 (약 40명 수강생, 기준 : 정확도)

