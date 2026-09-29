# Condemned: Criminal Origins 한글 패치

**한글화: 슬림쉐이디** · Xbox 360판 / Xenia · v0.7 ISO 테스트 배포

원본 ISO를 선택하면 별도의 한글 ISO를 만드는 패치입니다.
원본 ISO와 세이브 파일은 변경하지 않습니다.

## 다운로드 및 설치

**[한글 패치 v0.7 다운로드](https://github.com/slimshadykor-cmd/condemned-korean-patch-/raw/refs/heads/main/downloads/Condemned_Korean_ISO_v07.zip)** · [SHA-256 확인 파일](downloads/Condemned_Korean_ISO_v07.zip.sha256)

위 링크에서 패치 ZIP을 받으세요.

1. ZIP을 폴더에 전부 압축 해제합니다.
2. **`RUN_ISO_PATCH.bat`**를 실행합니다.
3. **패치하지 않은 원본 Condemned ISO**를 선택합니다.
4. 복사와 검사가 끝나면 원본 옆에 **`원본이름_Korean_v07.iso`**가 생성됩니다.
5. Xenia에서 생성된 ISO를 실행합니다. 콘솔 언어는 **English 또는 Korean**으로 설정합니다.

출력 위치에 ISO 한 개 크기만큼의 여유 공간이 필요합니다.
완료 메시지가 나올 때까지 패치 창을 닫지 마세요.
이미 같은 이름의 결과 파일이 있으면 덮어쓰지 않고 중단합니다.

원본으로 돌아가려면 기존 ISO를 실행하면 됩니다.

## 반영 내용

- 식별된 캠페인 대사, 문서, 목표, 메뉴와 조사 안내의 한국어 번역
- 한글 표시용 폰트
- 제보된 입력 안내 특수 태그 수정
- 확인된 상관(Dickenson) 대사의 반말 처리
- 메인 화면 오른쪽 위 **한글화: 슬림쉐이디** 표기

기존 v0.7 폴더 패치에서 사용한 번역·UI·폰트 데이터를 그대로 사용합니다.
이번 ISO 배포판에서는 적용 방식을 ISO 입력 방식으로 추가했습니다.

## 지원 환경과 검수 상태

**엔딩까지 실제 플레이하며 전수 검수한 상태는 아닙니다.**

- 대상: 제공된 원본 리소스와 일치하는 Xbox 360판 Condemned ISO
- 실행 대상: Xenia
- 패처 작성 대상: Windows 10/11, Windows PowerShell 5.1
- 설치 로직 검사 환경: Linux PowerShell 7.4.6
- 사용자 테스트: 초반 게임 화면과 한글 UI 확인
- ISO 패처 검사: 실제 원본 리소스를 사용한 테스트용 ISO에서 적용, 원본 보존, 전체 결과 파일 해시, 잘못된 입력 거부 확인
- 남은 확인: 실제 게임 ISO로 패치 후 Xenia 부팅, 전체 캠페인과 엔딩의 게임 내 표시

실제 ISO 부팅과 전체 플레이 확인이 남아 있어 테스트 배포로 안내합니다.
지원 판본과 다르거나 이미 수정된 ISO는 강제로 적용하지 않고 중단합니다.
분할 ISO와 압축 컨테이너는 지원하지 않습니다. 실기기 구동은 검증하지 않았습니다.

## 테스트 스크린샷

아래는 한글화 작업 중 사용자가 직접 올린 게임 화면입니다.
새 ISO 배포판을 실행해 촬영한 화면은 아닙니다.

![한글 대사 표시](docs/images/korean-dialogue.png)

![한글 진행 안내 표시](docs/images/korean-objective.png)

## 문제 제보

이 저장소의 **Issues**에 다음 내용을 남겨 주세요.

- 사용한 패치 버전과 Xenia 버전
- 문제가 발생한 장면 또는 설치 단계
- 번역 문제: 전체 문장이 보이는 스크린샷
- 설치 문제: 오류 메시지 또는 패치 폴더의 `iso_patch_error.txt`

공개 글에 오류 화면을 올릴 때 개인 이름이 포함된 파일 경로는 가려도 됩니다.

## 상세 안내와 소스

- [자세한 설치 안내](patcher/README_KR.txt)
- [ISO 패처 소스](patcher/IsoPatcher.cs)
- [적용 방식 및 검증 범위](patcher/source/NOTES_ISO_v07.md)
- [검사 결과](patcher/source/verification_ISO_v07.txt)
- [변경 내역](CHANGELOG.md)
- [폰트 라이선스](patcher/FONT_LICENSE.txt)
- [Xenia 참조 라이선스](patcher/XENIA_LICENSE.txt)

게임 ISO와 게임 실행 파일은 포함하지 않습니다.

## 배포 파일 확인

파일: `Condemned_Korean_ISO_v07.zip` · 크기: 3,822,421바이트

SHA-256:

```text
92e83d3c9324f2d40a56a7f0d67815f52646d431dbd96faeaffac40f7599e57f
```
