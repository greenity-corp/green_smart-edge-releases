# GreenSmart Edge 릴리즈

이 저장소는 **Edge 제품의 승인된 공개 릴리즈만** 제공합니다. 현재 게시된 제품 릴리즈는 없습니다.

- 릴리즈 목록: [Edge Releases](https://github.com/greenity-corp/green_smart-edge-releases/releases)
- 전체 구성요소 안내: [GreenSmart 릴리즈 홈](https://github.com/greenity-corp/green_smart-deploy)

## 분리 원칙

여기에는 Edge 전용 설치·업데이트·복구 안내와 출고 파일 또는 검증된 이미지 집합 참조만 게시합니다. Cloud 또는 Controller 파일을 이 저장소의 릴리즈에 첨부하지 않습니다. 다른 구성요소와의 호환성은 해당 릴리즈 설명에서 **버전과 링크로만** 표시합니다. 개발 소스, 내부 시험 자료, 운영 설정, 배포 자동화, 인증정보는 게시하지 않습니다.

## 출고 기준

릴리즈 태그는 `edge-vMAJOR.MINOR.PATCH`, 제목은 `Edge vMAJOR.MINOR.PATCH` 형식으로 사용합니다. Edge의 5개 이미지가 함께 출고되는 경우 동일한 검토 소스 커밋과 각 이미지의 불변 digest를 가진 **하나의 검증된 Edge 이미지 집합**으로 표시합니다. 각 릴리즈에는 Edge 자체 시험, 통합 QA, 보안·설치·복구 검증, 호환 가능한 Cloud·Controller 버전, 변경 이력, SHA-256 체크섬 및 서명 검증 방법을 기록합니다. 승인된 Edge 산출물만 첨부하고, 필요한 경우 SBOM과 출처 증거를 함께 제공합니다. QA와 출고 승인이 끝나기 전에는 릴리즈를 게시하지 않습니다.
