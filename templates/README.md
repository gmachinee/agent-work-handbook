# 문서 템플릿

| 템플릿 | 작성할 내용 | 저장 위치 |
| --- | --- | --- |
| [rule.md](rule.md) | 채택할 작업·판단 기준 | `knowledge/rules/<topic>/` |
| [guide.md](guide.md) | 반복 작업의 절차와 완료 기준 | `knowledge/guides/<topic>/` |
| [reference.md](reference.md) | 외부 자료의 요약과 해석 | `knowledge/references/<topic>/` |
| [pattern.md](pattern.md) | 직접 확인한 방법과 검증 결과 | `knowledge/patterns/<topic>/` |

## 사용하는 방법

1. 필요한 템플릿을 해당 저장 위치에 복사하고 구체적인 파일명을 정합니다.
2. `id`를 고유 값으로 바꾸고, 제목과 요약을 작성합니다.
3. 날짜, 적용 범위, 태그, 본문 자리표시자를 실제 값으로 바꿉니다.
4. 외부 자료를 사용했다면 `sources`를 채웁니다. 출처 URL은 원문을 직접 확인한 주소로 기록합니다.
5. 필요한 경우 `reviewed_on`, `language`, `related`, `supersedes`를 추가합니다.
6. 소유자의 검토 후 `status: active`로 변경합니다.

템플릿의 `YYYY-MM-DD`, `kb-replace-with-unique-id`, 예시 출처 주소와 안내용 본문은 작성 전에 바꾸는 자리표시자입니다. 사용하지 않는 본문 항목은 제거하고 필수 메타데이터는 유지합니다.

문서의 자세한 기준은 [문서 형식](../docs/document-format.md)을 따릅니다. 이 폴더의 파일은 기본 RAG 색인 대상 밖입니다.
