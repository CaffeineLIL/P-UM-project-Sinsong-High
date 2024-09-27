# 신송고 프로젝트 양질의 교육<br>

메인 주제 : AI가 인종에 따라 해당 문화권의 전문분야를 어떻게 편향되어 평가하는가?
=
해당 문화권 = 미국

그럼 AI가 인종별 소득에 따라 편향된 시각을 가지게 되는가?

인종별로 임금의 격차가 있는데, 해당 자료를 가지고 AI가 특정 인종(백인,흑인, 아시아인 등..)에 대해 편향된 시각을 가지고 있지 않을까? (예시 : 그림 생성 AI를 사용했을 때, CEO는 백인 남성이다.)
인종별 임금격차가 왜 해당 문제에 대한 문제상황 제시가 되는가?미국은 자본주의 사회니까, 소득에 따른 생활 수준이 다르니 여기서 자연스레 사회 갈등이 일어날 수 밖에 없고, 그렇게 사람들마다 편향된 시각이 생겨서 해당 데이터를 AI가 그대로 학습한 게 아닐까?


프로젝트 구성 순서 초안

생성형 AI가 발전하면서 인종에 따라 해당 문화권의 전문분야를 어떻게 편향되어 평가하는가에 대해 알아봄 
-> 이 주제에서 어떤 것이 문제가 되는가? 
-> 그렇다면 왜 문제일까? 아마 인종별로 전체적인 소득 격차가 다르기 때문이지 않을까? 

-> 이에 대한 근거로, 아래 ‘Racial and Ethnic Achievement Gaps’에서 발췌한 것처럼, “주별 인종적 성취 격차는 주별 인종적 사회경제적 불평등과 밀접한 상관관계가 있습니다.” 라는 연구 결과를 근거로 삼아보았다.

-> “주별 인종적 성취 격차는 주별 인종적 사회경제적 불평등과 밀접한 상관관계가 있을 것이다”의 주제로 파이썬 분석을 진행하기로 결정. 

-> 파이썬 분석을 통해 “Earnings Disparity Race and Ethnicity Data” 데이터셋을 활용해서 미국 주 마다 소득 격차가 얼마나 나는지 비교하여 가설과 비교해보자.

파이썬을 통해 인종별로 소득 격차가 존재한다는 사실은 알아냈습니다. 
(코드 설명 필요하면 멘토가 설명)
https://github.com/CaffeineLIL/P-UM-project-Sinsong-High
(해당 코드 올려놨습니다)

왜? 인종별 소득 격차가 편향을 만들어 내는가?
-> 소득 격차가 존재하여 상대적 부유층이 양질의 교육을 받을 기회가 더 많아 교육 기회의 격차가 생기게 된다. 해당 차이는 그대로 AI가 학습할 수 있는 데이터의 양의 차이를 만들어 내므로, 해당 데이터는 경제적으로 어려운 사람들을 과소 대표하게 된다. 이는 자연스럽게 AI의 편향으로 이어지게 된다.

그럼 앞으로 우리는 AI가 이런 편향을 가지지 않도록 어떤 노력을 기울여야 하는가?

사회적 해결법, 기술적 해결법으로 나누어서 프로젝트 발표 구성하기
● AI 기술이 계속 발달하고 있음에 따라 편향성 문제에 대한 지속적인 감시와 심도있는 연구등이 필수적이기 떄문에 AI윤리위원회같은 기관을 만들어 모델링 할 때 검토하고 모델링하기
● 인종 때문에 생기는 고용이나 임금에서의 차이도 발생해서는 안 되지만, 인종에 관계없이 양질의 교육을 동등하게 받을 수 있도록 해야 한다.
● 저소득층 및 소외된 인종 집단에 대한 조기 교육 기회를 확대해서 차이를 줄인다
● AI를 학습시키기 위한 자료를 모으고 분류해서 편향된 정보를 삭제해주는 사이트가 있으면 좋을거 같습니다.
● AI가 데이터를 학습할때 편향된 데이터인지 판단하는 시스템을 만들어서 편향되지 않은 데이터만 학습하도록 한다
● 
===========================================================================

--참고 문헌--
2020 U.S. Population More Racially, Ethnically Diverse Than in 2010 (census.gov) 
미국 내 인종의 다양성이 10년사이 예상치보다 훨씬 증가함

https://www.dol.gov/agencies/ofccp/about/data/earnings/race-and-ethnicity
미국 전국/ 주 별 인종별 임금 차이 분포 및 노동자 수

Differences in Work Hours and Hours Preferences by Race in the U.S.: Review of Social Economy: Vol 56, No 4 (tandfonline.com)
미국 내 인종 별 근무시간 선호도

https://www.bls.gov/cps/cpsaat11.htm
미국 인종 별 직업 분포도

Racial representation in professional occupations: By the numbers | Economic Policy Institute (epi.org)
전문직 별 미국 인종 분포도 및 분석

https://www.pewresearch.org/short-reads/2023/04/20/most-americans-say-racial-bias-is-a-problem-in-the-workplace-can-ai-help/
기사 - 인종에 따라 미국내 구인에 문제를 겪고 있는데, AI가 도움을 줄 수 있을 것인가? 

https://www.bls.gov/opub/reports/race-and-ethnicity/2018/
기사 - 2018년 인종 및 민족별 노동력 특성

https://www.apple-economy.com/news/articleView.html?idxno=74240
AI편견‧인종차별 철폐 내건 ‘챗블랙GPT’ 등장

사용 파일
https://cepa.stanford.edu/educational-opportunity-monitoring-project/achievement-gaps/race/
Racial and Ethnic Achievement Gaps – 아래 사진 참고
