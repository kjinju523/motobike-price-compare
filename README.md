# motobike-price-compare
오토바이 부품 가격 비교 서비스

이 프로젝트는 쇼핑사이트(ex.Webike 등)에서 오토바이 부품 가격을 수집하여
사용자가 필요로 하는 부품을 저렴하게 찾을 수 있게 돕는 가격비교 서비스 입니다. 

# 주요 기능
 - 쇼핑몰에서 데이터 수집 (크롤링)
 - 오토바이 모델별 정비 부품 자동 조회
 - 가격 비교 및 필터 기능 제공
 - AWS 기반 인프라 구성 (EC2, S3, RDS 등)
 - 현 위치 기반 추천 정비센터 


# 기술 사용 스택
 - Python : 크롤러 및 백엔드 API
 - Flask or FaskAPI : 웹 API 서버
 - MySOL or PostgreSQL
 - Linux (Riocky Linux9)
