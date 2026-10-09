# Condemned: Criminal Origins 한글 패치

**한글화: 슬림쉐이디**  
Xbox 360판 / Xenia용 · **v0.9 검수 수정 통합판** · 2026-10-09

Condemned: Criminal Origins Xbox 360판을 한국어로 플레이하기 위한 비공식 한글 패치입니다.

## 다운로드

**[ISO용 v0.9 패치 다운로드](https://github.com/slimshadykor-cmd/condemned-korean-patch-/raw/refs/heads/main/Condemned_Korean_ISO_v09.zip)**  
파일: `Condemned_Korean_ISO_v09.zip` · 3,870,390바이트

[폴더용 v0.9 패치 다운로드](https://github.com/slimshadykor-cmd/condemned-korean-patch-/raw/refs/heads/main/Condemned_Korean_UI_v09.zip)  
파일: `Condemned_Korean_UI_v09.zip` · 4,711,573바이트

**이전 번역과 수정 사항을 모두 포함한 통합 패치입니다. 이전 패치를 먼저 적용할 필요가 없습니다.** 사용하는 게임 형식에 맞는 파일 하나를 받으세요.

## ISO 설치 방법

1. ISO용 ZIP의 압축을 **전부 해제**합니다.
2. 압축을 푼 폴더의 **`RUN_ISO_PATCH.bat`**를 실행합니다.
3. 패치하지 않은 **원본 Condemned Xbox 360 ISO**를 선택합니다.
4. 완료 메시지가 나올 때까지 기다립니다.
5. 생성된 `원본이름_Korean_v09.iso`를 Xenia에서 실행합니다. 콘솔 언어는 English 또는 Korean으로 설정합니다.

**기존 v0.7·v0.8 등 패치된 ISO에 덧씌우지 마세요. 원본 ISO에 v0.9를 적용해 새로 만드세요.**

원본 ISO는 보존되고 새 ISO가 별도로 생성됩니다. 출력 드라이브에 ISO 한 개 크기만큼의 여유 공간이 필요합니다. 이 저장소에는 원본 게임 ISO가 포함되어 있지 않습니다.

## 폴더 설치 및 업데이트

1. 게임과 Xenia를 종료합니다.
2. `Condemned_Korean_UI_v09` 폴더를 게임의 `default.xex`, `Layer0.Arch00`와 나란히 놓습니다.
3. 새 패치 폴더의 **`RUN_FIX.bat`**를 실행합니다.
4. `FIX APPLIED`가 나오면 해당 게임 폴더의 `default.xex`를 실행합니다.

기존 v0.1~v0.8 폴더 패치 사용자는 원본 백업(`.bak`)과 설치 기록(`.state.json`)을 유지해야 업데이트할 수 있습니다. ISO 패치판에서 추출한 폴더에는 이 업데이트를 적용하지 말고 깨끗한 원본을 사용하세요. 자세한 방법과 복원 안내는 ZIP 안의 `README_KR.txt`에 있습니다.

## v0.9 변경 사항

검수에서 확인한 오역·번역 누락 후보·용어 불일치 **8곳**을 수정했습니다.

| 항목 | 수정 내용 |
| --- | --- |
| Desktop | 바탕 화면 → 책상 상판 |
| Draw | 꺼내기 → 무승부 |
| Boot | 장화로 번역 |
| 체크포인트 저장 공간 부족 안내 | 내부 코드 대신 한국어 안내문 수록 |
| Rate | 비율 → 공격 속도 |
| SMG | 부정확한 기관총 대신 표준 약어 SMG 사용 |
| Last Weapon | 마지막 무기 → 직전 무기 |
| 로딩 팁 22 | 피해 표시 → 공격력 표시 |

SMG는 기관단총을 뜻합니다. 기존 문자열 공간에 정확한 한국어 명칭이 들어가지 않아 약어를 유지했습니다. 일부 잔존 항목의 실제 본편 표시 여부는 미확인입니다.

기존 캠페인 대사·문서·목표·메뉴 번역과 로딩 팁 43개 ID의 번역이 포함되어 있습니다. 이번 수정 외의 대사·글꼴·UI 레이아웃은 v0.8과 같습니다.

## 검수 범위

문자열 용량·태그·글꼴 참조, 압축 데이터, 아카이브 위치와 크기, 최종 배포 ZIP의 무결성을 검사했습니다. 확인한 데이터 범위에서 튕김을 유발할 구조 오류는 발견되지 않았습니다.

**실제 v0.9의 Xenia 플레이와 엔딩까지의 완주 검수는 아직 완료하지 않았습니다.** 자막 잘림·음성 싱크·실행 환경에 따른 문제는 추가 제보가 필요합니다. 설치기 실행 시험을 포함한 버전별 검사 범위는 ZIP 안의 `QA_KR.txt`에 구분해 기록했습니다.

## 문제 제보

번역 누락·오역·글자 깨짐·잘린 문장·패치 오류는 [Issues](https://github.com/slimshadykor-cmd/condemned-korean-patch-/issues)에 남겨 주세요.

가능하면 **챕터와 장면, 스크린샷, 사용한 패치 버전과 Xenia 버전**을 함께 알려 주세요.

## 파일 확인 및 이전 버전

다운로드 파일의 SHA-256은 [SHA256SUMS_v09.txt](SHA256SUMS_v09.txt)를 참고하세요.

이전 배포본도 보관합니다: [v0.8 ISO](https://github.com/slimshadykor-cmd/condemned-korean-patch-/raw/refs/heads/main/Condemned_Korean_ISO_v08.zip) · [v0.7 ISO](https://github.com/slimshadykor-cmd/condemned-korean-patch-/raw/refs/heads/main/Condemned_Korean_ISO_v07.zip)

원본 게임 데이터는 직접 준비해야 합니다. 이 저장소는 한글 패치만 배포합니다.

---

**Korean Translation / Patch: 슬림쉐이디**
