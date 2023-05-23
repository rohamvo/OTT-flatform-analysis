# OTT-flatform-analysis
A plan to enhance competitiveness through various indicators of OTT platform
![슬라이드0001](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/c64b421e-054e-43d0-826a-c45d4b79d8ea)
![슬라이드0002](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/22adeab0-8359-4299-a7ee-950cb9ce114a)
![슬라이드0003](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/8237423c-3d7a-4fe5-b770-0fdb41d5afff)
![슬라이드0004](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/cd62a1f8-89d6-4b70-8ecd-953f2d3141da)
저희는 Netflix 직원이라는 가정하에  OTT 시장에서 우위를 선점하기 위한 방향성을 분석해보았습니다. 먼저 넷플릭스/디즈니 플러스 / 아마존 프라임/ 훌루 4곳의 플랫폼을 비교하기 위해 데이터 프레임을 전처리 및 시각화 하였고 , 두번째로 세대별 장르, 작품 타입을 시각화 하기 위해 크롤링 및 데이터 프레임을 통해 시각화 하였습니다 . 마지막으로 리뷰 데이터 사이트 ( imdb, metacrics, letterboxed) 리뷰들을 크롤링 하여 긍정 , 부정 리뷰 , 계절별 핵심 키워드를 Wordcloud로 시각화 하고 토픽 모델링까지 분석해보았습니다.
![슬라이드0005](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/25fe8001-e76b-4cd4-936d-4a3ce8174868)
![슬라이드0006](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/06564e51-677f-413d-8858-d826252e3050)
![슬라이드0007](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/f881a87c-da69-4f0b-8624-d04e92655bcb)
![슬라이드0008](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/61c776be-4945-4172-9a4d-19d4ad60fce7)
![슬라이드0009](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/e4770bdc-4596-4b01-adb6-bb27f25531b3)
첫번째 주제는 넷플릭스, 아마존 프라임, 디즈니 플러스, 훌루 4개의 플랫폼 데이터 프레임을 수집하여 각 플랫폼의 티비쇼, 영화 점유율을 비교하였고 두번째로 관람 등급 비중을 비교하였습니다. 마지막으로 업데이트 기간 즉 플랫폼에 작품을 업데이트 하는 시점 더불어 최신작을 제일 빨리 업데이트 하는 플랫폼은 어디인지 알아보았습니다. 
![슬라이드0010](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/51e57e2c-c95d-43f7-811f-51083ef732a7)
![슬라이드0011](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/1e1bf7f9-7d9d-4078-9996-436bf7cb9aad)
이에 대한 결과를 파이차트와 바그래프로 시각화하였습니다. 아마존 프라임에서는 영화 , 훌루에서는 티비쇼의 비중이 앞도적으로 높았습니다. 이는 각 매니아층을 끌어들이기 위한 마케팅 전략에 좋은 자료가 될 수 있을것 같습니다. 예를들면 아마존 프라임 입장에서는 영화 전문 플랫폼, 훌루의 입장에서는 티비쇼가 많은 플랫폼 이미지가 있는 또 다른 예로는 영화가 많은 아마존 프라임 혹은 티비쇼가 많은 훌루에서는 어떤 방식으로 홍보 하는지 자세하게 포스터 선정 및 줄거리 요약 설명 과연 고객이 작품에 매력을 느끼는지 등등 참고할 수 있을것 같습니다. 넷플릭스에서는 다른 OTT 플랫폼과는 차별화를 두어 자사 플랫폼만의 영화, 티비쇼를 기획하고 제작하는데 더 투자를 한다면 플랫폼만의 특정 매니아 고객을 더 끌여들일 수 있을 것으로 보여집니다.
![슬라이드0012](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/8fbed657-4299-424a-a4aa-97c71e733313)
![슬라이드0013](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/f9d213b3-54e1-4ea0-8529-306cab0a1afb)
왼쪽의 그래프는 4개 플랫폼을 한 캔버스에 비교하였고 오른쪽의 그래프는 플랫폼 각각의 관랍 등급 비중을 비교해보았습니다. 아마존 프라임에서는 다양한 관람등급의 작품을 보유하고 있지만 넷플릭스에서는 성인 등급의 작품이 압도적으로 많아 타겟 고객층이 성인인점 , 더불어 아직 다양한 관람 등급의 작품 업데이트가 부진해보이는 것을 알 수 있습니다. 디즈니 플러스는 영화 제작사 명성에 걸맞게 전체이용가 작품이 압도적으로 많은 비중을 차지하였습니다. 이런 점에서 넷플릭스와는 반대 성향의 플랫폼으로 넷플릭스에서 전체이용가 작품을 업데이트 할 때 디즈니 플랫폼을 참고할 점이 많을 것 같습니다. 
![슬라이드0014](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/f6981460-a0b1-4913-93f0-7a0e7b6b3ef1)
![슬라이드0015](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/3b5e9dae-d503-48f4-8fe6-fef4daca9ca2)
마지막으로 언제 작품을 업데이트 했는지 더불어 최신작을 제일 빨리 업데이트 하는 플랫폼은 어디인지 알아본 결과입니다. 각각의 데이터에서 date_added, realease_year 컬럼을 사용하였고 중복제거, nan값 제거를 하였습니다. 
이때 업데이트된 연도와 달 컬럼을 date_added 컬럼에서 추출하여 추가하였고 최신작을 제일 빨리 업데이트 하는 플랫폼을 알아보기 위해 앞서 추출한 연도에서 release_year(개봉 연도)를 빼는 연산 처리를 하여 최신작 업데이트 기간을 알 수 있습니다. 이후 연도와달별 컬럼을 그룹바이 하여 카운트해서 시각화를 해보았습니다. 

X축은 연도 , Y축은 작품수를 나타내는 시각화 자료
![슬라이드0016](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/297664a8-8278-4c5b-97be-3c0d733523a2)
![슬라이드0017](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/a7ca5014-1356-4da6-bdbf-027d54397a1e)
![슬라이드0018](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/42389906-04da-43a8-8fe1-4127019eec21)
![슬라이드0019](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/a8e274da-103d-4378-b5fe-f2d39537906b)
![슬라이드0020](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/eb09e155-7ee0-4e65-9b33-dfedf4afe2d7)
이를 동시에 비교해보면 아마존 프라임이 부진한 업데이트를 보인다고 하여도 4개의 플랫폼 중 업데이트 수가 가장 많고 꾸준한 업데이트를 보여주고 있습니다. 
![슬라이드0021](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/c875ff69-74a4-4b36-9dc8-f17c50ee1e06)
최신작 업데이트 기간을 알아보기 위해 update_period 컬럼을 사용하였고 update_period 가 0이면 그만큼 최근 개봉 작품을 플랫폼에 빠르게 업데이트 했음을 알 수 있습니다. 
왼쪽 시각화 한 결과 X축이 update_period, Y축이 작품수를 나타내고 각각의 그래프를 비교해보면 넷플릭스가 왼쪽으로 그래프가 몰려 있는것으로 보아 가장 최신작에 민감하고 디즈니는 옛날 작품도 많이 업데이트 되는 모습을 볼 수 있습니다. 아마존 프라임은 역시나 업데이트 작품 수가 많아서 인지 골고루 최신작, 옛날 작품도 골고루 업데이트 되는 모습을 확인 할 수 있습니다
![슬라이드0022](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/f50f1e84-d1ec-47e0-af65-5ece2e9aedf3)
이 또한 동시에 비교해보니 한눈에 비교하기 용이합니다. 아마존은 업데이트 하는 작품 수에 비해 트렌드에는 민감하지 않은 모습을 확인 할 수 있고 넷플릭스가 가장 최신작품에 민감한것을 알 수 있습니다. 
이를 마케팅에 이용하여 최신작을 가장 빨리 업데이트 하는 플랫폼이라는 타이틀을 가지고 홍보 전략에 이용하면 좋을 것 같습니다. 
![슬라이드0023](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/7ed676bf-21c6-4d8e-8d50-74a4ba34c72f)
두번째 주제로 영화 순위 TOP10 작품 중 세대별 비중을 파악하고, 어떤 세대가 어떤 장르를 좋아하는지 전체 장르의 세대별 비중 파악하고 , 마지막으로 앞서 OTT플랫폼별 티비쇼/ 무비 비중을 알아봤다면 이번에는 세대별 티비쇼/ 무비 비중을 파악하여 분석해보았습니다.
![슬라이드0024](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/76e81a81-746e-4291-b3cc-4c09404ea515)
![슬라이드0025](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/76161d5a-b42e-4d9e-9d34-974ec3b5b03f)
![슬라이드0026](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/ba3978bd-cd57-4dc5-956e-1424be869e56)
X축은 탑10 작품 , Y축은 이용자 수를 보여줍니다. 
전체적 비중은 Y세대가 가장 높으며, 우리가 집중해야할 OTT 사업의 주요 공략 대상이라고 할 수 있다 하여 Y세대의 장르별 트렌드를 파악할 필요가 있습니다 .
Z세대 또한 OTT 서비스나 최신 트렌드, IT에 접근성이 높은 ‘디지털 네이티브 세대’로 마케팅 대상에서 배제할 수 없을것으로 보입니다. 
![슬라이드0027](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/2bc38d1c-f00f-4e20-b42a-85df0b2df3da)
![슬라이드0028](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/0e716fac-982a-44f2-8e14-457e0eda9b99)
![슬라이드0029](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/707a5c8d-1691-4ede-990a-04b88d07b6ff)
![슬라이드0030](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/b71cca00-0b8c-494e-98c3-a9738455fe76)
장르별 전체 세대의 비중을 그래프로 나타내보니 Drama는 전 세대를 통틀어 인기가 많은 장르로 압도적인 상위권을 차지하는 것을 볼 수 있습니다. 
이는 주기적인 모니터링을 통해 타 플랫폼보다 빠르게 Drama 장르를 수입/제작하는 것이 필수적으로 요구됩니다. 
Animation 육아와 연관이 없는 baby-boomers를 제외한 부모세대 로 볼 수 있는 x, y 세대와 개방적인 젊은 z 세대는 Animation 비중이 높은것을 볼 수 있습니다
이는 만화에 개방적인 젊은 세대뿐만 아니라 매니아 계층이 점점 늘어나는 추세를 보여 매니아 계층이 늘어난 만큼 그들의 Needs를 충족할 필요가 있다고 생각됩니다. 
Comedy는 최근에 기존의 코미디 장르에서 벗어나 액션,드라마, 사극 등과 같은 여러 장르와 융합한 하이브리드 코미디 콘텐츠가 큰 인기를 얻고 있는 추세를 보입니다 
이때 타 플랫폼과는 다른 차별적으로 독자적인 코미디 장르를 제작하는 것도 경쟁력 강화에 도움이 될 것 같습니다. 
![슬라이드0031](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/51f319e8-8612-45be-9818-c453ea1dbfd0)
![슬라이드0032](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/0d9ab106-acf6-41be-ab38-070dcc322ecc)
전체 타입의 비중을 확인하면 영화가 2배이상 많지만 세대별 탑 100 비중은 티비쇼가 인기가 많은 것을 알 수 있습니다. 우리 넷플릭스 입장에서는 상대적으로 CG 나 연출이 많이 필요한 SF, SuperHero 같은 장르가 아닌 부담 없이 보기 좋은 Drama 장르와 현재 트렌드인 티비쇼 타입의 작품을 제작 및 업데이트시 참고하기 좋은 자료 같습니다. 더불어 티비쇼 타입의 작품이 인기 많은 이유 중 한가지로 러닝타임이 상대적으로 긴 영화보다 바쁜 현대사회에서 러닝타임이 짧은 작품 시청하는것을 선호하는 현대인들의 성향을 추측할 수 있습니다.  
![슬라이드0033](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/2519015b-001d-4c6d-8628-0712e9664263)
Flixpatrol 데이터 분석을 통해 우리는 Drama(TV/show) 장르가 모든 세대를 통틀어 가장 인기 있는 장르임을 알 수 있었습니다. 실제 사례로 넷플릭스는 한국의 TV Show ‘오징어게임’으로 1조원, ‘이상한 변호사 우영우’로 4천억을 벌어들인 경험이 있습니다. 그러나 Kaggle 데이터 분석 결과에서 Netflix의 Drama(TV/show) 장르의 비중은 30.4%에 그치고 있어 해당 장르에 대한 적극적인 수입 및 제작 활동을 한다면 더욱 많은 고객층 확보와 경제적인 발전이 예상됩니다. 

또한 Flixpatrol 분석 결과에서 현재 부모세대인 X, Y세대의 Animation 시청률이 높은 것은 육아를 위한 것으로 보이며 앞으로 OTT의 최대 고객이 될 수 있는 Z세대에서는 Animation이 최대 인기 장르이다. 하지만 현재 Netflix의 작품의 연령제한 비중을 보면 주로 17+로 성인 작품들이 대부분을 차지하고 있는 것으로 보이기 때문에 전체 OTT 플랫폼에서 가장 많은 고객층인 부모세대와 Z세대의 고객층을 확보하기 위해서는 적극적인 Animation 작품 제작 및 수입 활동이 필요할 것이다.

Update_period 분석에서 넷플릭스가 최신작에 민감한 플랫폼임을 볼 수 있어 최신작을 수입 및 제작에 비용적으로 더 투자하여 가장 빨리 업데이트 하는 플랫폼이라는 타이틀을 가지고 홍보 전략에 이용하면 좋을 것 같습니다. 
![슬라이드0034](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/016a44d5-3404-4662-8e73-e6baaa19e0b1)
세번째 주제로 리뷰 데이터 사이트 ( metacrics, letterboxed, IMDB) 리뷰들을 크롤링 하여 작품별 긍정 , 부정 리뷰 ,핵심 키워드 등 Wordcloud로 비교 하였습니다.
![슬라이드0035](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/ee22a92d-2d9c-477b-ba26-4d13697a1164)
![슬라이드0036](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/5951f81c-318c-4c33-a6ae-aceaf0e8741e)
![슬라이드0037](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/09d4a32e-45d2-47d0-9666-205517cc72f6)
해당 워드 클라우드는 레터박스에서 수집한 겨울왕국 리뷰입니다.리뷰 별점으로 긍정,보통, 부정로 분류하였고 긍정에 hope, energy, masterpiece 부정에 특별한 부정적인 단어는 안보이는것 같습니다. 
![슬라이드0038](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/ff18ccf5-74e5-47ee-89dd-8b99fdd9c051)
해당 워드 클라우드는 메타크릭스에서 수집한 겨울왕국 리뷰입니다. 긍정에 pretty, perfect , beautifuly 등 이 있고 부정에 suck 외에는 부정 단어는 보이지 않습니다. 
![슬라이드0039](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/4a669782-37be-4745-a112-522f40b6d418)
해당 워드 클라우드는 IMDB에서 수집한 겨울왕국 리뷰입니다.  이렇게 긍정  / 보통 / 부정 리뷰로 나누어 해당 개수를 통해 영화에 대한 전반적인 평가를 확인 할 수 있었습니다. 점수라는 평가 요소 외에도 타이틀별로 부정 평가의 특성이 갈리는 것을 볼 수 있습니다. 예를 들어 영화의 전반적인 평이 좋으면 보다 절제된 표현으로 WordCloud가 보이는 것을 알 수 있었습니다. 영화들의 리뷰를 통해 작품의 작품성을 판단할 수 있는 중요한 척도가 될 수도 있을것 같습니다. 
![슬라이드0040](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/f854eda1-c216-4a5e-8da5-90dd04456a59)
마지막 주제로 2022년 리뷰들을 계절별로, 달별로 워드클라우드화한 분석 결과입니다.
![슬라이드0041](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/1f486717-be73-4a1b-b949-f9f0de63b552)
![슬라이드0042](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/43c06e5e-ec74-49db-98f9-38b2f2813ae1)
워드클라우드의 결과를 왼쪽부터 으로 봄, 여름, 가을 , 겨울 순으로 정렬했을때 실제 영화 개봉 날짜 전 후로 해당 영화와 관련된 단어들이 자주 보이는것을 볼 수 있습니다. 22년 3월 1일에 개봉한 베트맨 영화는 개봉직전인 겨울 시즌 워드틀라우드에서도 보이고 개봉한 봄 시즌에는 더 크게 보이는것을 볼 수 있었습니다. 스파이더맨 노웨이홈도 22년 12월 15일에 개봉하여 해당 겨울 시즌 워드클라우드에 주인공인 피터, 스파이더 단어들이 키워드로 나온것을 볼 수 있습니다. 
![슬라이드0043](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/831ef72c-1dbd-41e6-9e06-c9d29ff307ea)
왼쪽이 1월~6월 , 오른쪽이 7월부터 12월로 나타나져 있는데 달별로 보아도 마찬가지로 3월 개봉인 베트맨 영화가 2월 키워드로 등장하는 것을 볼 수 있었고 4월에 개봉한 신비한 동뭉사전 덤블도어의 비밀도 4월에 덤블도어라는 키워드를 볼 수 있었습니다. 이를 통해 고객들이 영화가 개봉하기 전부터 해당영화에 기대를 많이하고 관심이 많은것을 알 수 있었고  여기서 코비드라는 단어도 키워드로 보여 이로 보아 해당 시대 반영을 리뷰를 통해서 알 수 있음을 볼 수 있었습니다. 이를 활용하여 어떤 시대를 주제로 작품을 선정하여 해당 주제를 메인으로 홍보하는 방안을 제안할 수 있습니다. 
![슬라이드0044](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/fd38262c-5df1-459c-9923-87b76bd5823c)
토픽 모델링 분석 결과입니다.
![슬라이드0045](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/557e391c-a717-483b-8610-f97301bf1f26)
![슬라이드0046](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/f75058f7-4c59-486c-a822-1fe24eaa5442)
![슬라이드0047](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/5688dec1-79f5-4481-9ca5-fdab16ce31d7)
![슬라이드0048](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/2fe1fcea-1115-44bc-adab-7c253f0cb67c)
5개의 topic으로 LDA를 한 결과 ‘Film’, ‘movie’같은 공통단어를 생각하여 lda_components_점수가 높은 단어기준  20개의 상위단어들을 추출하였습니다. 
공통된 단어들이 보이는 경우가 많은데 이는 똑같은 friend(친구)에 관한 영화라도 범죄물, 로맨스,미스터리 등 장르가 다양할 수 있기 때문이라고 생각됩니다.
이후 8807개의 description들에게 5개의 topic중 한가지가 할당되어 있는 것을 볼 수 있습니다 .
![슬라이드0049](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/e03f1228-0a49-4058-bed4-a19efde21300)
![슬라이드0050](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/5b485e68-aad3-40ce-9ace-beb2645edbca)
![슬라이드0051](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/166538ab-bda5-4c57-aa86-3fed9b5e37a2)
![슬라이드0052](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/059c6428-cec7-444c-9eef-06b1e1127a32)
![슬라이드0053](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/e164e7c3-2698-4d98-884a-37fe4e96f4a7)
![슬라이드0054](https://github.com/rohamvo/OTT-flatform-analysis/assets/117894782/b3f324d8-05d5-48dc-b220-6ee244a5741f)
