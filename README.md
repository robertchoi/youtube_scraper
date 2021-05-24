# youtube_scraper
YouTube 채널 ID를 입력하면 해당 채널에 속한 모든 비디오의 통계를 수집합니다.

# 사용한 패키지(모듈)
* Google API Python Client
* Pandas

# 동작환경
* python 3.6 >

# 동작 방식
* YouTube API Data v3 를 이용합니다.
* YouTube 채널명을 바탕으로 Uploads 플레이리스트 ID를 확인하고, 여기서 Video ID를 가져옵니다.
* Video ID 별로 한번씩 Data API를 조회하여, 필요한 데이터 (조회수, 좋아요, 싫어요, 코멘트, 등록일)을 가져옵니다.

# Disclaimer
* 개발자 아닌 사람이 짜서 코드가 지저분할 수 있습니다. 개선 의견이나 리팩토링 관련 도움을 주시면 저의 발전에 도움이 됩니다.
