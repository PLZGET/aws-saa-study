# AWS SAA Study OS

AWS Certified Solutions Architect – Associate (SAA-C03) 자격증 취득을 위한 개인 학습용 웹 대시보드입니다.

AWS 서비스별 핵심 개념을 학습하고, 실전형 시나리오 문제를 풀면서 시험 준비 상태를 점검할 수 있도록 제작했습니다.

문제 풀이부터 오답 분석, 학습 기록 관리, 실전 모의고사까지 하나의 웹사이트에서 이용할 수 있습니다.

### [AWS SAA Study OS 바로가기](https://plzget.github.io/aws-saa-study/index.html)
<img width="1828" height="909" alt="image" src="https://github.com/user-attachments/assets/8d0f4f86-611d-455e-b031-af66cd86ee0a" />


---

## 주요 기능

### 1. 실전 문제은행

- SET 1~5, 각 50문제씩 총 250문제 제공
- AWS SAA-C03 유형에 맞춘 시나리오 기반 문제
- 단일 선택 및 복수 선택 문제 지원
- 영역별 문제 풀이 및 정답률 확인
- 문제별 정답, 핵심 해설, 오답 분석 제공

### 2. PDF 기출 예상 문제

- 별도 PDF 예상 문제 163문제 제공
- 문제 및 해설 원문 확인
- PDF 원본 페이지 연결
- 기존 문제은행과 별도로 학습 가능

※ AWS 공식 기출문제가 아닌 학습용 예상 문제입니다.

### 3. 실전 모의고사

- 실제 SAA-C03 시험 형식을 참고한 모의고사
- 무작위 65문제 출제
- 제한 시간 130분
- 시험 종료 후 일괄 채점
- 영역별 정답률 및 취약점 분석

### 4. 오답노트 및 복습

- 틀린 문제 자동 저장
- 다시 풀고 싶은 문제 북마크
- 오답 문제 재풀이
- 문제별 복습 메모 작성

### 5. 학습 대시보드

- 전체 학습 진행률
- 날짜별 문제 풀이 기록
- 누적 정답률
- AWS 영역별 취약점 분석
- 모의고사 응시 결과 확인

### 6. 공개 AWS 문제은행 연동

- GitHub에 공개된 SAA-C03 연습문제 활용
- 영역별 문제 데이터 동기화
- 원본 문제 및 출처 확인

---

## 주요 학습 영역

| 영역 | 주요 서비스 및 개념 |
|------|-------------------|
| 보안 | IAM, IAM Role, KMS, AWS Organizations |
| 컴퓨팅 | EC2, Auto Scaling, Lambda |
| 스토리지 | S3, EBS, EFS, FSx |
| 네트워크 | VPC, Route 53, CloudFront, ELB |
| 메시징 | SNS, SQS, EventBridge |
| 데이터베이스 | RDS, Aurora, DynamoDB |
| 재해 복구 | RTO, RPO, Multi-AZ, Multi-Region |
| 서버리스 | Lambda, API Gateway, Step Functions |
| 비용 최적화 | Savings Plans, Reserved Instances, Spot |

---

## 기술 스택

- HTML5
- CSS3
- JavaScript
- LocalStorage
- GitHub Pages

별도의 백엔드 서버 없이 정적 웹사이트로 동작합니다.

## 학습 데이터 저장

문제 풀이 기록, 정답률, 오답노트, 북마크, 복습 메모는 브라우저의 LocalStorage에 저장됩니다.

- 동일한 브라우저에서 재접속 시 학습 기록 유지
- PC와 모바일 브라우저 간 자동 동기화는 지원하지 않음
- JSON 파일로 학습 기록 백업 및 복원 가능
- CSV 형식으로 풀이 기록 내보내기 지원

브라우저 데이터 삭제 시 학습 기록이 사라질 수 있으므로 정기적인 백업을 권장합니다.

---

## 실행 방법

### 웹사이트 접속

별도 설치 없이 PC 및 모바일 브라우저에서 접속할 수 있습니다.

https://plzget.github.io/aws-saa-study/index.html

### 로컬 실행

저장소를 클론한 후 `index.html`을 브라우저에서 열면 됩니다.

```bash
git clone https://github.com/PLZGET/aws-saa-study.git
```

일부 온라인 문제은행 기능은 인터넷 연결이 필요합니다.

---

## 참고 사항

- 본 프로젝트는 개인 학습 목적으로 제작되었습니다.
- AWS 및 Amazon Web Services의 공식 서비스가 아닙니다.
- 수록된 문제는 실제 시험문제와 동일함을 보장하지 않습니다.
- AWS 서비스 사양 및 시험 범위는 변경될 수 있습니다.
- 외부 문제은행과 PDF 자료의 저작권은 각 원저작자에게 있습니다.

---

**목표: AWS Certified Solutions Architect – Associate (SAA-C03) 합격**
