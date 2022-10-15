my blog : https://roboharco12.tistory.com/57?category=1064282     
Reference :
- https://github.com/michaeltinsley/Gridworld-with-Q-Learning-Reinforcement-Learning-
- https://realdiganta.medium.com/coding-the-gridworld-example-from-deepminds-reinforcement-learning-course-in-python-17d74335fcbc





*** 환경에서 정의되어야 하는 것
- Reward에 대한 정의
- 행동, 상태에대한 정의 -> 에이전트의 각 행동선택에대한 State의 변화 정의
   




*** 에이전트에서 정의되어야 하는것
- 행동을 선택하는 방법에대한 정의
- 학습 과정에 대한 정의




### Action Value Table vs State Value Table
- Action Value 방식은 Action Value에 대한Table과, Reward 파악을 위한 각 State별 Reward Table 두가지를 별도로 만들어줘야함.     
- 반면 State Value는 하나만 있으면 됨-> State Table에 그대로 Reward를 기입해주면 되기 때문