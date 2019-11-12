# WPS 12th

**웹 프로그래밍 스쿨 | 이한영 강사 교육과정**  

- [강사 블로그](https://lhy.kr/)
- [강의 영상](https://www.youtube.com/playlist?list=PLz_KHa75m7JUtFjfJf9hORIhtoHOTtkJl)

>  아래 예정 소요일수 및 과정은 강의 진행에 따라 달라질 수 있습니다



## 교육과정 안내

### 1. Python (6일)

> Django를 사용하기 위해 필요한 기본적인 파이썬 활용법을 배웁니다

- 개발환경 설정
  - pyenv, pyenv-virtualenv를 활용한 개발환경 설정
  - JupyterNotebook을 사용한 파이썬 스크립트 작성
- 파이썬 기본 문법
  - Variable, Number, String
  - Sequence Types
  - Data structures (List, Tuple, Set, Dictionary)
  - Compound statements (if, while, for, try, with)
  - Decorator
  - Generator
  - Function
  - Module, Package
  - Object, Class
  - Regular Expression
  - Exception
  - File IO
- 알고리즘 맛보기
  - 순차검색
  - 선택정렬
- 프로젝트
  - 웹툰 크롤링 프로젝트

### 2. Git (2일)

> 버전 관리 도구인 Git이 제공하는 기능들을 학습합니다

- 버전관리란?
- 로컬 환경에서의 작업
  - Untracked, Unmodified, Modified, Staged 상태의 이해
  - 변경 상태를 기록
    - add
    - commit
    - tag
  - 변경 상태를 확인
    - log
    - status
    - diff
  - 상태를 되돌리기
    - reset
    - stash
  - 리모트 저장소
    - remote
    - fetch
- 브랜치
  - 브랜치의 이해
  - branch를 사용한 브랜치 생성
  - checkout을 사용한 브랜치 이동
  - merge를 사용한 브랜치 병합
    - 충돌과 처리
  - rebase를 사용한 깔끔한 브랜치 병합

### 3. Django (12일)

> Django를 사용해 웹 애플리케이션을 제작해보며, 웹 프로그래밍의 개념과 여러 기술들을 학습합니다

- MVC패턴과 Django의 MTV패턴
- 튜토리얼
  - DjangoGirls Tutorial 따라하며 블로그 만들기
  - Django Tutorial 따라하며 설문조사 앱 만들기
- Django개념 학습
  - Model을 사용한 데이터베이스 테이블 구현
  - ORM과 QuerySet을 사용한 데이터베이스 사용
- 인스타그램 만들기
  - Bootstrap CSS Framework의 사용
  - Post List 구현
  - Post Detail 구현
  - 회원가입, 로그인 구현
    - Authentication의 이해
      - Session과 Cookie의 이해
    - Django CustomUser모델
  - Post Create 구현
    - CSRF의 이해
    - Form을 사용한 파일 업로드
  - Comment Create 구현
  - Post Like 구현
  - Following 구현
  - Facebook Login 구현
  - 메일 발송
    - Celery를 사용한 비동기 작업
  - Class-Based View로의 리팩토링

### 4. Django REST Framework (5일)

> Django는 프론트(웹 페이지)와 백엔드(데이터)를 합쳐 웹 사이트를 만드는 프레임워크입니다
> 클라이언트에서 프론트를 담당한다면, Django는 가진 데이터를 클라이언트에서 사용할 수 있는 API를 제공하는 역할을 해야합니다  
> 이를 위해 API제작 도구인 DRF사용법을 학습합니다

- RESTful API란?
- DRF 개념 학습
  - DRF Tutorial
  - Serialize/Deserialize, JSON의 이해와 Serializer, ModelSerializer의 활용
  - APIView
  - Generic APIView
  - API Guide 문서 학습
    - Authentication
    - Permission
    - Exception
- DRF 관련 도구
  - Postman을 사용한 API테스트
  - drf-yasg를 사용한 문서 자동화
- 인스타그램 프로젝트에 API추가

### 5. Docker (3일)

> Docker는 컨테이너 기반의 가상화 플랫폼이며, 최근 배포환경에서 필수적으로 사용되고 있는 기술입니다.  
> 프로젝트를 실행해보며 Docker의 개념과 활용법을 학습합니다

- Docker란?
- Docker를 사용한 이미지 실행
- Dockerfile을 사용한 커스텀 이미지 생성
- Docker를 사용한 Django프로젝트 실행

### 6. AWS, 배포(Deployment) (9일)

> 애플리케이션을 전 세계 어디서든 사용할 수 있도록 클라우드 플랫폼에 배포합니다. 여기서는 업계 점유율 1위인 AWS를 사용하며, 이전에 배운 Docker를 배포에 활용합니다

- 클라우드란?
- EC2에 배포
- Docker를 사용한 배포
- ElasticBeanstalk을 사용한 Docker배포

