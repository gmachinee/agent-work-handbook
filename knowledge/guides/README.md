# 작업 절차

반복하는 작업의 목표, 준비 조건, 순서, 완료 기준을 보관합니다. 정식 문서의 `kind`는 `guide`입니다.

- `product/`: IT 서비스·제품 기획, 조사·검증, 출시·개선 절차
- `implementation/`: 기능 구현과 수정 절차
- `review/`: 코드·콘텐츠·문서 검토 절차
- `content/`: 콘텐츠 기획과 제작 절차
- `writing/`: 자료 조사, 아티클 작성과 편집 절차

[작업 절차 템플릿](../../templates/guide.md)을 복사하고 실패 상황에 대한 대응 기준도 작성합니다.

## 활성 작업 절차

- [브랜치 병합 시 변경 보존 절차](implementation/git-merge-preservation.md) — 양쪽 변경 의도, i18n·rename과 기준 브랜치 변경의 중복 유입을 확인합니다.
- [테스트·CI 실패의 변경 귀속 확인](review/test-failure-attribution.md) — 기존 실패와 이번 변경의 실패를 근거로 구분합니다.
- [자기 완결적 검수 보고서 구성](review/self-contained-review-reports.md) — 기존 UI/UX 판정 기준을 반복하지 않고 유저 스토리별 실행·화면·근거를 연결합니다.

- [IT 서비스 기획·검증·개선 절차](product/service-planning.md) — 사용자·시장·경쟁 조사와 레퍼런스·벤치마킹을 검증·상세 설계·구현·성과 개선에 연결합니다. 작업별 준비 조건·단계 결과·완료 판단과 기업 자료의 근거·한계를 함께 관리합니다.
