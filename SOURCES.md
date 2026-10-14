# 자료 출처와 배포 조건

현재 제공 자료는 일본어13종·한국어16종·영어28종입니다. 아래 TOPIK·CEFR·EIKEN 출처 기록은
2026-10-12 사용자 요청으로 제거한 과거 자료의 출처 이력이며 현재 제공 안내가 아닙니다.

## TOPIK 어휘 한국어 → 영어 / 일본어

- 자료: `ko-en-topik.json`, `ko-ja-topik.json`
- 원본 사전: 국립국어원 한국어기초사전 — https://krdict.korean.go.kr
- 가공 데이터: basickorean/basickorean-vocab — https://github.com/basickorean/basickorean-vocab
- 원본 어휘 목록: https://github.com/julienshim/combined_korean_vocabulary_list
- 사전·가공 데이터의 배포 조건: Creative Commons 저작자표시-동일조건변경허락 2.0 대한민국 (CC BY-SA 2.0 KR) — https://creativecommons.org/licenses/by-sa/2.0/kr/
- 위 사전에서 파생한 두 카드팩도 CC BY-SA 2.0 KR로 제공합니다. 앱 프로그램 자체의 라이선스를 뜻하지 않습니다.
- 변경: 담아 카드 형식으로 변환, 대역이 확보된 어휘의 부분 수록, 의미별 카드 분리 및 발음 근사 표기 추가. 단어 수준은 추정값이며 공식 TOPIK 등급을 보증하지 않습니다.

## CEFR 영어 자료의 수준 분류

- CEFR-J Wordlist Version 1.5 — Yukio Tono / Tono Laboratory, Tokyo University of Foreign Studies (TUFS).
- 제공 저장소: https://github.com/openlanguageprofiles/olp-en-cefrj
- CEFR-J 수준 데이터는 위 저장소의 출처 표시 조건에 따라 사용합니다.
- Octanove Vocabulary Profile C1/C2 1.0 — Octanove Labs, CC BY-SA 4.0: https://creativecommons.org/licenses/by-sa/4.0/
- 변경: 중복 표제어 정리, 단계별 담아 카드 구성. 두 CEFR 파일의 뜻 대역에 사용한 사전별 정확한 원본과 배포 조건은 별도 확인 중입니다. 확인 전 모든 구성요소의 재배포 권한 검토가 끝났다고 주장하지 않습니다.

## JLPT / EIKEN

제공자가 작성한 자료의 원본 출처·생성 방식과 배포 권한을 확인 중입니다. JLPT 단계는 카드 notes에 명시된 난이도 추정이며 공식 지정 목록이 아닙니다.

## 한국어 교육과정 어휘 · 한영 / 한일

사용자 제공 ko-en-nikl-grade1~6.json 및 ko-ja-nikl-grade1~6.json. originalId의 nikl2017-rev20201117 표기를 보존했습니다. 파일 표기 기준 국립국어원 교육과정 1~6급 자료이며, 정확한 생성 방식·번역 및 재배포 조건은 이 파일만으로 전수 확인한 것으로 주장하지 않습니다. 공개 준비 시 꾸러미명만 답안 언어에 맞춰 변경했고 학습 내용은 유지했습니다. 위 과거 TOPIK 자료의 라이선스를 이 신규 자료에 자동 적용하지 않습니다.

## 새 CEFR A1~C2 · 영한 / 영일

2026-10-12 사용자 제공 cefr-A1~C2_en-ko.json 및 cefr-A1~C2_en-ja.json의 12종입니다. 기존에 제거한 통합 CEFR2종과 별개이며 새 파일의 ID·학습 내용·바이트를 그대로 공개했습니다. 단계·생성 방식·배포 조건을 이 파일만으로 전수 확인한 것으로 주장하지 않으며, 위 과거 CEFR 출처/라이선스를 신규 자료에 자동 적용하지 않습니다.

## 새 EIKEN · 영한 / 영일16종

2026-10-12 사용자 제공 5급~1급(준2급·준2+급·준1급 포함) 영한/영일16종입니다. 기존 제거한 통합 EIKEN2종과 별개이며 새로운 JSON 원본을 그대로 공개했습니다. 단계·원본 출처·생성 방식·배포 조건을 이 파일만으로 전수 확인한 것으로 주장하지 않습니다. 위 과거 자료 출처/라이선스를 신규 자료에 자동 적용하지 않습니다.

## 일반 지식 5종 · 2026-10-14 검수본

사용자 제공 수정본 5개(총 523장)를 원본 바이트 그대로 제공합니다. 카드 ID·내용·순서·꾸러미를 변경하지 않았습니다. 상식은 한국어/일본어 각 54장, 사자성어 102장, 국가·수도 195장, 원소기호 118장입니다. 신조어와 AI·테크는 제외했습니다.

- 일반상식: 우주·지구·생물·문화 사실을 NASA, NOAA, USGS, 박물관, UNESCO 등 기관 자료와 대조한 제공자 검수본입니다. [카드별 출처·검수 범위](references/knowledge-20261014/trivia-sources.json).
- 사자성어: 국립국어원 사전 자료를 대조하고 한국어 뜻·학습 예문으로 구성한 제공자 검수본입니다. [102장별 출처](references/knowledge-20261014/idioms-sources.json).
- 국가·수도: UNESCO 국가·수도 데이터, UN 회원국·옵서버 목록과 정부·국제기구 자료를 대조했습니다. 수도·정부 소재지·분산 기능과 지위 차이를 구분했습니다. 짧은 지리 설명은 전체 검토했으나 문장마다 독립적인 웹 출처를 확인한 것은 아닙니다. [범위·예외·카드별 출처](references/knowledge-20261014/capitals-sources.json).
- 화학 원소: IUPAC와 대한화학회 표준 주기율표를 사용한 제공자 검수본입니다. 원소 118개의 원자번호·기호·한국어 이름은 대한화학회 공식표와 대조했습니다. [출처·대조 기록](references/knowledge-20261014/elements-sources.json).

위 기록은 제공된 검수 근거이며 공인 번역·원어민 감수나 미래의 수도 변경까지 보증하는 자료가 아닙니다. 공식 자료의 명칭·사실 대조 기록을 보존하며, 기존 어휘 자료의 라이선스를 이 자료에 자동 적용하지 않습니다. 실제 앱 파서·무결성·합산 가져오기·재가져오기·임시 저장 및 재읽기는 배포 전에 검증했습니다. 개인 기기의 데이터와 앱 바이너리는 변경하지 않았으며 실제 기기 화면 검증은 별도입니다.
