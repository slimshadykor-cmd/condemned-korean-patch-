# 컨뎀드: 크리미널 오리진 Xbox 360 한글패치 v1.2

[**최신 패치 다운로드**](https://github.com/slimshadykor-cmd/condemned-korean-patch-/releases/download/v1.2/Condemned_Korean_ISO_v12.zip)

## v1.2 사용 환경 선택 기능 추가 — 2026-11-20

기존 패처에 **Xenia용 / Xbox 360 실기용** 선택을 추가했습니다. 버전과 기존 다운로드 주소는 유지합니다. 전에 받은 ZIP은 다시 받아 주세요.

| 선택 | 적용 내용 |
|---|---|
| Xenia용 | 게임 한글화 + 기존 도전 과제 한글화 및 프로필 문구 처리 |
| Xbox 360 실기용 | 같은 게임 한글화 + **원본 XEX 유지/복원**, 프로필 처리 생략 |

지원 원본 ISO 또는 기존 v1.1/v1.2 한글 ISO에 적용할 수 있습니다. 기존 Xenia용 v1.2도 실기용으로 전환할 수 있습니다.

### 설치

1. 아래 **Condemned_Korean_ISO_v12.zip**을 받고 전체 압축을 풉니다.
2. 게임을 종료하고 **RUN_PATCH.bat** 실행 → 사용 환경 선택 → ISO 선택.
3. Xenia용만 Xenia/content 폴더를 추가 선택합니다.
4. 완료 창에 표시된 ISO를 사용합니다. 입력은 보존되며 같은 폴더에 별도 생성됩니다.

- Xenia용 결과: `_Korean_v12.iso`
- 실기용 결과: `_Korean_Xbox360_v12.iso`
- 이미 선택한 환경의 v1.2는 검증 후 재사용합니다. 기존 다른 결과는 덮어쓰지 않습니다.
- [상세 안내](https://github.com/slimshadykor-cmd/condemned-korean-patch-/blob/main/README.md)
- [저장소 대체 다운로드](https://github.com/slimshadykor-cmd/condemned-korean-patch-/raw/refs/heads/main/Condemned_Korean_ISO_v12.zip)
- [이번 변경/검증 기록](https://github.com/slimshadykor-cmd/condemned-korean-patch-/blob/main/Condemned_v12_Target_Selection_20261120.txt)

### 실기 호환 및 검수 범위

사용자 제보에서는 기존 v1.2 실행 시 실기에서 튕겼으나, XEX를 원본으로 교체한 뒤 초반 구동에 성공했습니다. 실기용은 이 방식을 반영하며 **도전 과제 설명은 영어로 남을 수 있습니다.** 수정 게임을 실행할 수 있는 기존 실기 환경이 필요하며, ISO 추출/전송 도구는 포함하지 않습니다.

원본→실기용과 Xenia용→실기용의 전체 결과 ISO가 일치하고, 반대 방향 전환도 일치함을 확인했습니다. 실기용 XEX는 원본과 바이트 단위로 같으며, 번역/폰트/UI/버튼 표시 데이터는 기존 v1.2 그대로입니다. 입력 보존·프로필 미변경·재실행·덮어쓰기 차단도 검사했습니다.

검증은 실제 원본 XEX와 아카이브 앞 8MiB를 넣은 합성 ISO, Linux PowerShell 7.4.6에서 수행했습니다. **Windows 선택 창과 Xbox 360 실기에서의 직접 실행·엔딩 검수는 미완료입니다.** 도전 과제 수정의 정확한 실기 실패 원인도 아직 확정하지 않았습니다.

기존 버튼 안내 18곳 복원, 한글 설명, 메인화면 **한글화: 슬림쉐이디  v1.2**, 나머지 번역은 유지합니다. Xenia 실행파일·공용 설정·저장 경로·Dummy HDD 이름은 변경하지 않습니다.

기존 main 브랜치 v07~v11 ZIP 주소와 v1.1 릴리스의 호환 다운로드도 동일한 선택형 패치로 갱신합니다. 과거 고정 커밋/태그의 소스 기록은 유지됩니다.

### 파일 확인

파일 크기: 4,276,859바이트

```text
280d82330f4344a976db716ba8432f24cdb68c7031999afae5ec7936817fde28  Condemned_Korean_ISO_v12.zip
```

한글화: 슬림쉐이디
