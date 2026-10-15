# GreenSmart Edge 공개 안내·릴리즈

Edge는 현장 서비스와 로컬 제어를 담당하는 GreenSmart 구성요소입니다. 이 저장소에는 승인된 Edge 설치·업데이트·복구 안내와 Edge 산출물 또는 검증된 이미지 집합 참조만 게시합니다.

- [GreenSmart 전체 안내](https://github.com/greenity-corp/greensmart_release)
- [Edge Releases](https://github.com/greenity-corp/green_smart-edge-releases/releases)
- 함께 사용하는 [Cloud 안내](https://github.com/greenity-corp/green_smart-cloud-releases) · [Controller 안내](https://github.com/greenity-corp/green_smart-controller-releases)

## 현재 게시 상태

2026-10-15 기준 이 GitHub 채널의 Releases는 0개입니다. 이 채널의 게시 현황과 기존 제품 운영·설치 현황을 구분합니다. 검증된 공개 버전 조합과 설치 명령은 아직 이 안내에 게시하지 않았습니다.

기존 고객의 설치 파일 전달은 Cloud의 **설치 및 업데이트** 메뉴를 따릅니다. 공개 GitHub 채널의 추가로 고객 다운로드 권한이나 기존 설치 경로가 바뀌지는 않습니다.

## 이미지 집합과 호환성

Edge의 5개 이미지가 함께 출고되면 같은 검토 소스 커밋과 각 이미지의 불변 digest를 가진 하나의 검증된 이미지 집합으로 안내합니다. 서로 다른 집합의 이미지를 임의로 섞어 호환된다고 판단하지 않습니다.

각 공개 릴리즈에는 다음을 기록합니다.

- Edge 버전·원본 커밋 식별자·이미지 집합 식별자와 각 digest
- 실제 검증한 Cloud·Controller 버전 조합과 지원 조건·미지원 조합
- 적용 순서, 사전 상태 확인, 설치·업데이트 중단 조건과 복구 절차
- 공개 산출물의 SHA-256 체크섬, 서명·출처 검증 방법과 알려진 제한

체크섬만으로 서명 검증을 대신하지 않습니다. 적용 전에 해당 릴리즈에 게시한 검증 방법과 현장 조건을 확인하세요. 아직 게시하지 않은 주소·키·설치 명령을 추측해 사용하지 마세요.

## 검증과 공개 범위

태그 형식은 `edge-vMAJOR.MINOR.PATCH`, 제목은 `Edge vMAJOR.MINOR.PATCH`를 사용합니다. 이는 표기 규칙이며 현재 지원 버전을 선언하지 않습니다.

출고 전에는 Edge 자체 시험, Cloud·Controller와의 계약·회귀 및 필요한 이전/새 버전 혼용 시험을 완료합니다. 화면 기능은 관련 브라우저 E2E 시나리오에 반영하고, 실제 장치 설치·업데이트·복구 결과를 개발 환경 시험과 구분해 기록합니다. 생략·미실행은 통과로 표시하지 않으며 출고 승인을 받은 뒤 게시합니다.

Cloud·Controller 파일은 각 전용 채널로 안내합니다. 소스 코드·상세 내부 설계·운영 설정·인증정보·고객 데이터는 공개하지 않습니다. 필요한 SBOM·출처 증거도 공개 대상을 검토한 뒤 제공합니다.
