# 파이썬 Cybos plus, Cybos 5 대신증권 API 이용 프로그램

## ✔︎프로그램 실행전 주의사항
아나콘다 32bit, 파이참 32bit (관리자 권한 실행), 파이썬 환경 변수 설정 등...

1. 업종 코드로 해당 업종 종목 데이터 가져온다
2. 해당 업종 종목의 평균 PER 을 계산한다
3. 평균 PER 에 EPS 를 곱하고 해당 데이터를 적정 주가로 본다
4. 현재 주가와 적정 주가를 비교해 '고평가', '저평가', '평균' 3가지 단계로 나누어준다
5. tkinter 를 이용해 테이블로 해당 데이터 보여준다

table ex)
이름 | 현재가 | PER | EPS | 적정주가 | 평가
---|---|---|---|---|---|
SBank|3200.0|32.0|100|8000.0|저평가