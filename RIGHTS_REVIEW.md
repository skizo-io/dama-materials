# AI 생성 자료의 생성 경위·이용 점검

기준: 현재 `catalog.json`의 71종·93,189장. 이번 변경은 안내 문서만 대상으로 하며 단어·뜻·ID·예문과 다운로드 목록은 변경하지 않습니다.

## 생성 경위와 공통 점검 기준

2026-10-21 제공자 설명에 따르면 모든 자료는 AI로 생성했습니다. 특정 교재·사전·웹페이지 원문을 지정하거나 제공해 작성하도록 요청하지 않았습니다. AI가 실제로 참고한 자료는 확인되지 않았으며, 사용한 AI 서비스·모델·생성 로그와 당시 이용 조건은 제공되지 않았습니다. 아래 표시는 제공자 설명 기준이며 생성 로그를 독립 검증했다는 뜻은 아닙니다.

기존 ‘66종 우선 재배포 권한 확인’ 분류를 위 생성 경위에 맞춰 대체합니다. 66종 전체가 외부 원문을 재배포하거나 일괄 허가를 받아야 하는 자료라는 근거는 확인되지 않았습니다. 외부 자료를 전혀 사용하지 않았다는 보증이나 모든 권리가 확인됐다는 선언도 아닙니다.

- AI 서비스가 확인되면 생성 당시 결과물의 배포·상업 이용 조건을 점검합니다. 서비스나 출처를 추측해 기재하지 않습니다.
- 특정 교재·사전 등의 표현을 실제로 가져온 사실이 확인되면 해당 파일·카드·구성요소에 한해 이용 조건과 필요한 허가·고지를 확인합니다. 긴 뜻풀이·설명·예문이 특정 원문을 실질적으로 재현하는지도 점검 대상입니다.
- 번역·읽기·예문·난이도·사실의 정확성은 별도로 검토합니다. 시험명·급수는 학습 분류이며 공식 제공·승인을 뜻하지 않습니다.
- 사실 대조용 참고자료는 생성 원문이나 재배포 허가 증거와 구분합니다. 이 목록은 새로운 라이선스나 재사용 허락을 부여하지 않습니다.

## 현행 파일 목록

현행 파일을 빠짐없이 표시하는 목록이며 파일마다 외부 허가가 필요하다는 표시가 아닙니다.

## JLPT·일본어 문법 12종

AI 생성 자료입니다. JLPT 단계·문법 설명·번역·예문의 정확성은 별도 검토 대상입니다.

| 공개 파일 | 방향 | 카드 | 현재 상태 |
| --- | --- | ---: | --- |
| `dama-ja-ko-jlpt-n1.json` | JA→KO | 4,151 | AI 생성(제공자 설명 기준) |
| `dama-ja-ko-jlpt-n2.json` | JA→KO | 2,361 | AI 생성(제공자 설명 기준) |
| `dama-ja-ko-jlpt-n3.json` | JA→KO | 2,107 | AI 생성(제공자 설명 기준) |
| `dama-ja-ko-jlpt-n4.json` | JA→KO | 666 | AI 생성(제공자 설명 기준) |
| `dama-ja-ko-jlpt-n5.json` | JA→KO | 745 | AI 생성(제공자 설명 기준) |
| `dama-ja-ko-grammar.json` | JA→KO | 740 | AI 생성(제공자 설명 기준) |
| `dama-ja-en-jlpt-n1.json` | JA→EN | 4,151 | AI 생성(제공자 설명 기준) |
| `dama-ja-en-jlpt-n2.json` | JA→EN | 2,361 | AI 생성(제공자 설명 기준) |
| `dama-ja-en-jlpt-n3.json` | JA→EN | 2,107 | AI 생성(제공자 설명 기준) |
| `dama-ja-en-jlpt-n4.json` | JA→EN | 666 | AI 생성(제공자 설명 기준) |
| `dama-ja-en-jlpt-n5.json` | JA→EN | 745 | AI 생성(제공자 설명 기준) |
| `dama-ja-en-grammar-v2.json` | JA→EN | 740 | AI 생성(제공자 설명 기준) |

## NIKL 한국어 12종

AI 생성 자료입니다. 파일명·내부 ID의 NIKL 표기는 보존하지만 그 표기만으로 국립국어원 원자료를 직접 이용했거나 공식 제공 자료라고 판단하지 않습니다.

| 공개 파일 | 방향 | 카드 | 현재 상태 |
| --- | --- | ---: | --- |
| `ko-en-nikl-grade1.json` | KO→EN | 735 | AI 생성(제공자 설명 기준) |
| `ko-en-nikl-grade2.json` | KO→EN | 1,100 | AI 생성(제공자 설명 기준) |
| `ko-en-nikl-grade3.json` | KO→EN | 1,655 | AI 생성(제공자 설명 기준) |
| `ko-en-nikl-grade4.json` | KO→EN | 2,200 | AI 생성(제공자 설명 기준) |
| `ko-en-nikl-grade5.json` | KO→EN | 2,365 | AI 생성(제공자 설명 기준) |
| `ko-en-nikl-grade6.json` | KO→EN | 2,580 | AI 생성(제공자 설명 기준) |
| `ko-ja-nikl-grade1.json` | KO→JA | 735 | AI 생성(제공자 설명 기준) |
| `ko-ja-nikl-grade2.json` | KO→JA | 1,100 | AI 생성(제공자 설명 기준) |
| `ko-ja-nikl-grade3.json` | KO→JA | 1,655 | AI 생성(제공자 설명 기준) |
| `ko-ja-nikl-grade4.json` | KO→JA | 2,200 | AI 생성(제공자 설명 기준) |
| `ko-ja-nikl-grade5.json` | KO→JA | 2,365 | AI 생성(제공자 설명 기준) |
| `ko-ja-nikl-grade6.json` | KO→JA | 2,580 | AI 생성(제공자 설명 기준) |

## CEFR 영어 12종

AI 생성 자료입니다. CEFR 수준 표기는 특정 외부 어휘 목록의 직접 사용이나 공식 승인을 입증하지 않습니다.

| 공개 파일 | 방향 | 카드 | 현재 상태 |
| --- | --- | ---: | --- |
| `cefr-A1_en-ko.json` | EN→KO | 820 | AI 생성(제공자 설명 기준) |
| `cefr-A2_en-ko.json` | EN→KO | 1,135 | AI 생성(제공자 설명 기준) |
| `cefr-B1_en-ko.json` | EN→KO | 1,889 | AI 생성(제공자 설명 기준) |
| `cefr-B2_en-ko.json` | EN→KO | 2,539 | AI 생성(제공자 설명 기준) |
| `cefr-C1_en-ko.json` | EN→KO | 4,071 | AI 생성(제공자 설명 기준) |
| `cefr-C2_en-ko.json` | EN→KO | 1,269 | AI 생성(제공자 설명 기준) |
| `cefr-A1_en-ja.json` | EN→JA | 820 | AI 생성(제공자 설명 기준) |
| `cefr-A2_en-ja.json` | EN→JA | 1,135 | AI 생성(제공자 설명 기준) |
| `cefr-B1_en-ja.json` | EN→JA | 1,889 | AI 생성(제공자 설명 기준) |
| `cefr-B2_en-ja.json` | EN→JA | 2,539 | AI 생성(제공자 설명 기준) |
| `cefr-C1_en-ja.json` | EN→JA | 4,071 | AI 생성(제공자 설명 기준) |
| `cefr-C2_en-ja.json` | EN→JA | 1,269 | AI 생성(제공자 설명 기준) |

## EIKEN 영어 16종

AI 생성 자료입니다. EIKEN 시험명·급수는 학습 안내이며 공식 어휘 목록·기출문장 제공을 뜻하지 않습니다.

| 공개 파일 | 방향 | 카드 | 현재 상태 |
| --- | --- | ---: | --- |
| `eiken-5kyu_en-ko.json` | EN→KO | 611 | AI 생성(제공자 설명 기준) |
| `eiken-4kyu_en-ko.json` | EN→KO | 544 | AI 생성(제공자 설명 기준) |
| `eiken-3kyu_en-ko.json` | EN→KO | 646 | AI 생성(제공자 설명 기준) |
| `eiken-pre2kyu_en-ko.json` | EN→KO | 1,659 | AI 생성(제공자 설명 기준) |
| `eiken-pre2pluskyu_en-ko.json` | EN→KO | 951 | AI 생성(제공자 설명 기준) |
| `eiken-2kyu_en-ko.json` | EN→KO | 1,099 | AI 생성(제공자 설명 기준) |
| `eiken-pre1kyu_en-ko.json` | EN→KO | 2,696 | AI 생성(제공자 설명 기준) |
| `eiken-1kyu_en-ko.json` | EN→KO | 3,517 | AI 생성(제공자 설명 기준) |
| `eiken-5kyu_en-ja.json` | EN→JA | 611 | AI 생성(제공자 설명 기준) |
| `eiken-4kyu_en-ja.json` | EN→JA | 544 | AI 생성(제공자 설명 기준) |
| `eiken-3kyu_en-ja.json` | EN→JA | 646 | AI 생성(제공자 설명 기준) |
| `eiken-pre2kyu_en-ja.json` | EN→JA | 1,659 | AI 생성(제공자 설명 기준) |
| `eiken-pre2pluskyu_en-ja.json` | EN→JA | 951 | AI 생성(제공자 설명 기준) |
| `eiken-2kyu_en-ja.json` | EN→JA | 1,099 | AI 생성(제공자 설명 기준) |
| `eiken-pre1kyu_en-ja.json` | EN→JA | 2,696 | AI 생성(제공자 설명 기준) |
| `eiken-1kyu_en-ja.json` | EN→JA | 3,517 | AI 생성(제공자 설명 기준) |

## 초등 한자 읽기·쓰기 12종

AI 생성 자료입니다. 학년별 분류만으로 외부 설명·예문을 직접 가져왔다고 판단하지 않습니다. 한자 배당·읽기·뜻의 정확성은 별도 검토 대상입니다.

| 공개 파일 | 방향 | 카드 | 현재 상태 |
| --- | --- | ---: | --- |
| `shogaku1_reading.json` | JA→JA | 80 | AI 생성(제공자 설명 기준) |
| `shogaku1_writing.json` | JA→JA | 80 | AI 생성(제공자 설명 기준) |
| `shogaku2_reading.json` | JA→JA | 160 | AI 생성(제공자 설명 기준) |
| `shogaku2_writing.json` | JA→JA | 160 | AI 생성(제공자 설명 기준) |
| `shogaku3_reading.json` | JA→JA | 200 | AI 생성(제공자 설명 기준) |
| `shogaku3_writing.json` | JA→JA | 200 | AI 생성(제공자 설명 기준) |
| `shogaku4_reading.json` | JA→JA | 202 | AI 생성(제공자 설명 기준) |
| `shogaku4_writing.json` | JA→JA | 202 | AI 생성(제공자 설명 기준) |
| `shogaku5_reading.json` | JA→JA | 193 | AI 생성(제공자 설명 기준) |
| `shogaku5_writing.json` | JA→JA | 193 | AI 생성(제공자 설명 기준) |
| `shogaku6_reading.json` | JA→JA | 191 | AI 생성(제공자 설명 기준) |
| `shogaku6_writing.json` | JA→JA | 191 | AI 생성(제공자 설명 기준) |

## 스페인어 A1 2종

AI 생성 자료입니다. A1은 학습 수준 안내이며 공식 제공 자료를 뜻하지 않습니다. 어휘·번역·발음·예문의 정확성은 별도 검토 대상입니다.

| 공개 파일 | 방향 | 카드 | 현재 상태 |
| --- | --- | ---: | --- |
| `dama-spanish-a1-ko.json` | ES→KO | 456 | AI 생성(제공자 설명 기준) |
| `dama-spanish-a1-ja.json` | ES→JA | 456 | AI 생성(제공자 설명 기준) |

## 일반 지식 5종

AI 생성 자료이며 별도의 사실 대조 기록이 있습니다. 대조 기록은 생성 원문이나 이용 허가 증거가 아닙니다. 참고자료는 [SOURCES.md](SOURCES.md)를 확인하세요.

| 공개 파일 | 방향 | 카드 | 현재 상태 |
| --- | --- | ---: | --- |
| `dama-trivia-ko.json` | KO→KO | 54 | AI 생성 / 별도 사실 대조 기록 있음 |
| `dama-trivia-ja.json` | JA→JA | 54 | AI 생성 / 별도 사실 대조 기록 있음 |
| `dama-idioms-ko.json` | KO→KO | 102 | AI 생성 / 별도 사실 대조 기록 있음 |
| `dama-capitals-ko.json` | KO→KO | 195 | AI 생성 / 별도 사실 대조 기록 있음 |
| `dama-elements-ko.json` | KO→KO | 118 | AI 생성 / 별도 사실 대조 기록 있음 |

## 추가 사실이 확인되면 남길 기록

사용한 AI 서비스·모델·생성일·당시 이용 조건·생성 로그가 확보되면 확인된 범위만 기록합니다. 실제 외부 원문 이용이 확인되면 해당 부분과 정확한 출처·이용 조건·필수 고지를 연결합니다. 모르는 출처나 라이선스를 AI 추정으로 채우지 않습니다.

구 TOPIK·CEFR·EIKEN 6개 통합본과 과거 통합 JLPT 4파일·구 일영 문법 1파일은 위 현행 목록과 구분합니다. 이번 정리는 제공 중단 파일을 복구하거나 재공개하지 않습니다. 과거 안내의 출처·라이선스 주장을 현행 자료에 자동 적용하지 않습니다.
