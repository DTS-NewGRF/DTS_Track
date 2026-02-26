# Diversity Track Set 다양성 선로세트 /DTS_Track
![DTS_Track_board](https://github.com/DTS-NewGRF/DTS_Track/blob/main/docs/DTS_Track_board.png)
**다양성 선로세트**는 <br>
2024년 3월 28일 DTS 오브젝트 차량기지를 호환하기 위해 제작되었습니다.<br>

[Github release 페이지](https://github.com/DTS-NewGRF/DTS_Track/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
[1.05] 곧 등록시작합니다. <br>

## 인게임 등록
[1.04] 2026.02.25 <br>
[이슈외작업]
* 선로간 연결자동설치 오류 복원 (2026.02.21)
* 협궤선로 코드 변경적용 / 일본열차셋 호환적용 (2026.02.24)

[이슈작업]
* [선로추가] 고무차륜 (지하) / AGT Track (Underground) ([#39](https://github.com/DTS-NewGRF/DTS/issues/39)) (2026.02.01)
* [선로변경] 도시철도 (지하) 차량기지 변경 ([#40](https://github.com/DTS-NewGRF/DTS/issues/40)) (2026.02.01)
* [선로변경] 도시철도 3궤조 (지하) 차량기지 변경 ([#41](https://github.com/DTS-NewGRF/DTS/issues/41)) (2026.02.01)
* [선로변경] 고속철도 (지하) 차량기지 그래픽 변경 ([#42](https://github.com/DTS-NewGRF/DTS/issues/42)) (2026.02.01)
* [선로추가] 초고속선 (지하) / Very High Speed (Underground) ([#43](https://github.com/DTS-NewGRF/DTS/issues/43)) (2026.02.01)
* [버그] 노반(지하) 그래픽 문제 발생 ([#44](https://github.com/DTS-NewGRF/DTS/issues/44)) (2026.02.01)
* 선로 명칭 변경 (협궤 및 광궤선로 추가 대비) ([#45](https://github.com/DTS-NewGRF/DTS/issues/45)) (2026.02.23)
* [선로추가] 협궤 일반선 선로 (1067mm) / Narrow gauge Nomal Speed Tracks (1067mm) ([#46](https://github.com/DTS-NewGRF/DTS/issues/46)) (2026.02.23)
  * [버그] 협궤 일반선 선로, 협궤 일반선 전기선로 터널 그래픽 오류 ([#51](https://github.com/DTS-NewGRF/DTS/issues/51)) (2026.02.25)
* [선로추가] 협궤 일반선 전기선로 (1067mm) / Narrow gauge Nomal Speed Tracks (Electrified, 1067mm) ([#47](https://github.com/DTS-NewGRF/DTS/issues/47)) (2026.02.23)
  * [버그] 협궤 일반선 선로, 협궤 일반선 전기선로 터널 그래픽 오류 ([#51](https://github.com/DTS-NewGRF/DTS/issues/51)) (2026.02.25)
* [선로추가] 협궤 일반선 도심전기선로 (1067mm) / Narrow gauge Nomal Speed Tracks (Urban, Electrified, 1067mm) ([#48](https://github.com/DTS-NewGRF/DTS/issues/48)) (2026.02.24)
* 협궤선로 호환을 위한 추가작업 필요 ([#50](https://github.com/DTS-NewGRF/DTS/issues/50)) (2026.02.25)
* 협궤 일반선 선로 (1067mm) 선로코드 변경 ([#52](https://github.com/DTS-NewGRF/DTS/issues/52)) (2026.02.25)

## 등록기준
### 공통사항
기본 템플릿과 일치하지 않을 경우 적용이 보류된다. 하지만, 그외 자료는 제한을 두지 않고, 적용하고 있다.

### 깃허브 릴리즈 및 온라인컨텐츠 등록
기본 자료는 본 깃허브 릴리즈를 통해 메인 업로드를 기준으로 한다. <br>
릴리즈 등록시 프리 릴리즈가 아닌 최종 릴리즈로 등록된다. <br>
온라인 컨텐츠는 매달 등록되는것으로 정의한다. <br>
매달 기준 최종 깃허브 릴리즈가 온라인컨텐츠로 등록되는 것과 같다. <br>

## 개발
### 빌드하는 방법
이 NewGRF를 빌드하려면 [NML](https://github.com/OpenTTD/nml)과 **Python 3**이 필요합니다. <br> 
터미널 쉘에서 ``make``를 실행하세요. Windows 환경이라면, 그 전에 명령 프롬포트를 열고 ``bash``를 입력하세요.  <br>
``make clean``을 입력하면 모든 생성된 파일이 초기화됩니다.
