# black-and-white-racism_naver-movie-comment_analysis
데이터포트폴리오
201602321 이병걸
# 주제 : 미국 인종차별을 주제로한 영화를 선정해 네이버 댓글 형태소 분석 후, 비교분석 수행
### 1.배경 : 최근 2020년 5월 25일에 미국 경찰의 과잉진압으로 비무장 상태의 흑인 남성 조지 플로이드가 사망한 사건이 발생하였다. 이를 계기로 미국 전역에서 인종차별에 항의하는 시위가 확산되었으며 현재까지도 인종차별은 미국뿐 만이 아닌 사회적인 문제점 중 하나이다. 세계에서 흑인의 경제력과 문화 수준이 가장 높으며 완전히 미국화되어 있는데도 불구하고 흑인문제가 가장 심각한 곳이 미국이다.
### 2.목적 : 인종차별을 주제로 한 영화를 선정해 영화의 네이버 댓글에서 높은 평점의 댓글과 낮은 평점의 댓글을 내용을 텍스트 마이닝 방법을 통해 밝히고 비교분석 함으로써, 한국 사람들의 인종 차별에 대한 생각과 사회적으로 문제가 되는 인종 차별 문제의 원인을 탐색한다.
### 3.대상 : 미국의 인종차별을 주제로 하고 있는 영화 Get out, 그린 북, 히든 피겨스의 네이버 영화 평점/리뷰의 댓글을 통해 분석. (Get out의 댓글 9909건, 그린 북의 댓글 7119건, 히든피겨스의 댓글 3859건)
### 4.방법 : 네이버 영화 평점 및 댓글에 대해서 colab을(konlpy) 통한 형태소 분석 후, 낮은 평점과 높은 평점을 비교 분석하며 언어분석 수행.
#### -world cloud를 통한 시각화 
![image](https://user-images.githubusercontent.com/74230474/102796569-d1256400-43f1-11eb-92ee-481ee0b34bbe.png) get out 
![image](https://user-images.githubusercontent.com/74230474/102796676-f3b77d00-43f1-11eb-9c9c-5af0764e9ffd.png) 그린 북 
![image](https://user-images.githubusercontent.com/74230474/102796850-337e6480-43f2-11eb-8d26-d290b43a5636.png) 히든 피겨스 

#### 피벗테이블
![image](https://user-images.githubusercontent.com/74230474/102797887-a5a37900-43f3-11eb-8598-9d8df74e8360.png) get out (명사)

![image](https://user-images.githubusercontent.com/74230474/102797608-46ddff80-43f3-11eb-9c23-e1f8daab6f05.png) get out (형용사)

![image](https://user-images.githubusercontent.com/74230474/102797710-6ecd6300-43f3-11eb-906b-b88e030a3ca2.png) 그린 북 (명사)

![image](https://user-images.githubusercontent.com/74230474/102797956-bf44c080-43f3-11eb-8df1-4a6d0866b8c4.png) 그린 북 (형용사)

![image](https://user-images.githubusercontent.com/74230474/102797984-cbc91900-43f3-11eb-845b-dc8236cb679b.png) 히든 피겨스 (명사)

![image](https://user-images.githubusercontent.com/74230474/102797733-7a208e80-43f3-11eb-9232-b98ab83c5c24.png) 히든 피겨스 (동사)

![image](https://user-images.githubusercontent.com/74230474/102798010-d71c4480-43f3-11eb-8c37-b7b0722eebe2.png) 히든 피겨스 (형용사)
