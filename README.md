# sinkhole_detector

# Intuition
대도심에서의 싱크홀 사태 -> 제대로 발표되지 않는 취약 지반 정보 (집값 때문이라는 내부 고발식 정보 유츌이 있었음) -> 싱크홀이 일어나기 좋은 위치를 알리자!

# How will it work?
- 땅의 울림, 공진의 정보를 파악하여 싱크홀이 일어날 확률이 높은 지반 정보를 실시간으로 서버에 올리자
- 모델의 baseline은 지하철 공사 정보에 대한 정보 위치를 가지고 공사하는 위치 바로 위 그리고 공사하지 않는 곳(+ 주변에 물이 없는 곳)을 가지고 단단한 지반인지 아닌지에 대한 confidence를 얻어보자
- 모델을 직접 실험해보자
