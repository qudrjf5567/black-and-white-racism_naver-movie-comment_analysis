# black-and-white-racism_naver-movie-comment_analysis
데이터포트폴리오
201602321 이병걸
# 주제 : 미국 인종차별을 주제로한 영화를 선정해 네이버 댓글 형태소 분석 후, 비교분석 수행

### -피벗 테이블을 통해 낮은 평점의 댓글과 높은 평점의 댓글을 비교 분석한 결과 유의미한 결과를 확인할 수 있었다.

### 1.배경 : 최근 2020년 5월 25일에 미국 경찰의 과잉진압으로 비무장 상태의 흑인 남성 조지 플로이드가 사망한 사건이 발생하였다. 이를 계기로 미국 전역에서 인종차별에 항의하는 시위가 확산되었으며 현재까지도 인종차별은 미국뿐 만이 아닌 사회적인 문제점 중 하나이다. 세계에서 흑인의 경제력과 문화 수준이 가장 높으며 완전히 미국화되어 있는데도 불구하고 흑인문제가 가장 심각한 곳이 미국이다.
### 2.목적 : 인종차별을 주제로 한 영화를 선정해 영화의 네이버 댓글에서 높은 평점의 댓글과 낮은 평점의 댓글을 내용을 텍스트 마이닝 방법을 통해 밝히고 비교분석 함으로써, 한국 사람들의 인종 차별에 대한 생각과 사회적으로 문제가 되는 인종 차별 문제의 원인을 탐색한다.
### 3.대상 : 미국의 인종차별을 주제로 하고 있는 영화 Get out, 그린 북, 히든 피겨스의 네이버 영화 평점/리뷰의 댓글을 통해 분석. (Get out의 댓글 9909건, 그린 북의 댓글 7119건, 히든피겨스의 댓글 3859건)
### 4.방법 : 네이버 영화 평점 및 댓글에 대해서 colab을(konlpy) 통한 형태소 분석 후, 낮은 평점과 높은 평점을 비교 분석하며 언어분석 수행.
#### -world cloud를 통한 시각화 
![image](https://user-images.githubusercontent.com/74230474/102796569-d1256400-43f1-11eb-92ee-481ee0b34bbe.png) get out 
![image](https://user-images.githubusercontent.com/74230474/102796676-f3b77d00-43f1-11eb-9c9c-5af0764e9ffd.png) 그린 북 
![image](https://user-images.githubusercontent.com/74230474/102796850-337e6480-43f2-11eb-8d26-d290b43a5636.png) 히든 피겨스 

#### -피벗테이블(동사, 형용사, 명사)
![image](https://user-images.githubusercontent.com/74230474/102797887-a5a37900-43f3-11eb-8598-9d8df74e8360.png) get out (명사)

![image](https://user-images.githubusercontent.com/74230474/102797608-46ddff80-43f3-11eb-9c23-e1f8daab6f05.png) get out (형용사)

![image](https://user-images.githubusercontent.com/74230474/102797710-6ecd6300-43f3-11eb-906b-b88e030a3ca2.png) 그린 북 (명사)

![image](https://user-images.githubusercontent.com/74230474/102797956-bf44c080-43f3-11eb-8df1-4a6d0866b8c4.png) 그린 북 (형용사)

![image](https://user-images.githubusercontent.com/74230474/102797984-cbc91900-43f3-11eb-845b-dc8236cb679b.png) 히든 피겨스 (명사)

![image](https://user-images.githubusercontent.com/74230474/102797733-7a208e80-43f3-11eb-9232-b98ab83c5c24.png) 히든 피겨스 (동사)

![image](https://user-images.githubusercontent.com/74230474/102798010-d71c4480-43f3-11eb-8c37-b7b0722eebe2.png) 히든 피겨스 (형용사)

get out과 그린 북에서는 동사에 대한 피벗 테이블에서는 크게 유의미한 결과를 찾기가 힘들어서 참고하지 않았다.



#### -비교 분석 결과

피벗테이블을 통해 종합해서 고려해볼 때, 3개의 영화에서 모두 낮은 평점을 부여한 영화 시청자들은 사회적인 문제인 인종차별에는 크게 관심이 없으며 영화가 주는 사회적인 문제에 대한 메시지나 의미 해석을 중요시하기보다는 단순히 재미, 유흥의 측면에서 영화를 감상했으며 킬링 타임을 위하여 영화를 감상했음을 알 수 있었다. 반면에 높은 평점을 부여한 시청자들은 흑백 인종차별 때문에 흑인이 여러 가지 난제에 부딪히는 것을 보고선 그 당시의 사회적 분위기에 공감하며 인종차별에 대해 문제 의식을 어느 정도 가지고 영화를 감상했음을 알 수 있다. 하지만 댓글에서 자주 사용된 ‘흑형’이라는 표현을 흑인을 우상시하는 표현으로 생각하며 사용했으리라 짐작되는데 이는 사실 그들이 느끼기에 피부색을 들먹이면서 스테레오 타입을 씌우는 단어이기에 높은 평점을 부여한 시청자들 또한 인종차별에 대한 문제점은 인식하고 있지만 상대방은 불편할 수도 있는 단어를 무의식 중에 빈번하게 사용하는 것을 확인할 수 있었다. 

## -결론 

우리 한국 사회에는 아직 인종차별에 대한 인식적인 노력이 부족함을 알 수 있다. 본문에서 알 수 있듯이, 인종차별 관련 영화를 감상하고 낮은 평점을 부여한 영화 시청자들은 사회적인 문제인 인종차별에는 크게 관심이 없으며 단순한 재미를 위해 영화를 감상했음을 알 수 있었다. 높은 평점을 부여한 시청자들은 인종차별 영화를 감상하고선 영화가 주는 메시지나 의미적인 부분에서 인종차별에 대한 해석과 문제 의식을 어느 정도 가지고는 있었으나, ‘흑형’과 같은 표현을 많이 사용하는 것으로 보아 무엇이 인종차별적 행위인지, 혹은 발언인지를 인식하지 못하고 있었음을 알 수 있었다. 통계자료까지 살펴본 결과 인종차별에 대해 아예 인식하지 못하고 있는 경우가 10%를 웃도는 경우를 확인할 수 있었다. 인종차별은 미국뿐만이 아닌 전 세계가 해결해야 하는 사회적인 문제임에도 불구하고 이를 인지조차 하지 못한 사람의 비중이 작긴 하지만 존재한다는 것과 인종차별이 잘못된 것임은 알고 있으나 본인도 모르는 사이에 인종차별적 발언이나 행위를 빈번히 하는 것까지 고려한다면 우리는 앞으로 이러한 문제점에 대해 시민들의 인식적인 노력과 더불어 교육적인 부분을 강화해 나갈 필요성이 있다고 생각된다. 
