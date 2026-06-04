# Quilo 다운로드 사이트

Quilo(실험 보고서 생성기 데스크톱 앱)의 공개 다운로드 페이지.

- **사이트**: GitHub Pages → https://fakeminjun7321.github.io/quilo-app/
- **설치파일(dmg/exe)**: 이 저장소의 **Releases**에 업로드. 사이트 버튼은 `releases/latest/download/...` 고정 링크라 버전이 올라가도 안 깨진다.
- **Mac 앱 소스**: 별도 저장소 `lab-report-mac` (비공개)
- **Windows 앱 소스**: (추후) 별도 저장소

## 새 버전 올리는 법

1. 코드 저장소에서 `npm run dist` 로 설치파일 빌드
2. 이 저장소의 최신 Release에 **같은 파일명으로 교체** 업로드
   - macOS: `Quilo-mac-arm64.dmg`, `Quilo-mac-x64.dmg`
   - Windows(추후): 예) `Quilo-win-x64.exe` — 준비되면 `index.html`의 Windows 버튼만 활성화
3. 끝. 사이트 버튼은 고정 링크라 자동으로 새 파일을 가리킨다.
