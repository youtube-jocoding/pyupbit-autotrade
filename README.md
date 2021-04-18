# 파이썬 비트코인 투자 자동화 강의 코드
## by 유튜브 조코딩 채널

### pyupbit 라이브러리를 활용하여 upbit 거래소에서 비트코인 자동매매를 하는 코드입니다.

#### test.py : 잔고 조회 (1강)
#### backtest.py : 백테스팅 코드 (2강)
#### bestK.py : 가장 좋은 k 값을 찾는 코드 (2강)
#### bitcoinAutoTrade.py : 변동성 돌파 전략 비트코인 자동매매 코드 (2강)
#### bitcoinAutoTradeWithMA.py : 변동성 돌파 전략 + 15일 이동평균선 이상 비트코인 자동매매 코드 (2강)
#### bitcoinAutoTradeWithSlack.py : 위 코드에 슬랙 붙여 놓은 것 (2강)
#### 강의 보러가기:  https://youtube.com/playlist?list=PLU9-uwewPMe3KKFMiIm41D5Nzx_fx2PUJ

#### 위 코드는 "파이썬을 이용한 비트코인 자동매매 (개정판)"을 참고하여 제작되었습니다.
#### 참고 문헌: https://wikidocs.net/book/1665

### Ubuntu 서버 명령어
현재 경로 상세 출력: ls -al
경로 이동: cd 경로
vim 에디터로 파일 열기: vim bitcoinAutoTrade.py
vim 에디터 입력: i
vim 에디터 저장: :wq!
백그라운드 실행: nohup python bitcoinAutoTrade.py > output.log &
실행되고 있는지 확인: ps ax | grep test.py
