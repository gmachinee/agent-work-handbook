# 보관 문서

사용을 마쳤거나 새 문서로 대체된 지식 문서를 보관합니다.

- `status`를 `archived`로 변경하고 원래 `id`와 `kind`를 유지합니다.
- 원래 종류와 주제 폴더를 유지해 이동합니다. 예: `archive/rules/writing/example.md`.
- 이동된 문서를 가리키는 상대 링크를 갱신합니다.
- 대체 문서가 있다면 보관 문서 본문에 링크를 남기고, 새 문서에 `supersedes`를 기록합니다.

보관 문서는 기본 검색에서 제외하고 과거 기록 조회 요청에서 활용합니다.

## 보관된 문서

| 문서 | 대체 문서 |
| --- | --- |
| [레퍼런스 우선 UI/UX 설계 지침](rules/design/reference-first-uiux.md) | [UI/UX 통합 설계·검수 지침](../knowledge/rules/design/universal-uiux.md) |
