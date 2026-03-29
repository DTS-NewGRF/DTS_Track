# Diversity Track Set 다양성 선로세트 /DTS_Track
![DTS_Track_board](https://github.com/DTS-NewGRF/DTS_Track/blob/main/docs/DTS_Track_board.png)
**다양성 선로세트**는 <br>
2024년 3월 28일 DTS 오브젝트 차량기지를 호환하기 위해 제작되었습니다.<br>

[Github release 페이지](https://github.com/DTS-NewGRF/DTS_Track/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
[1.06]<br>
* [버그] 3궤조 LIM 차량기지 눈 그래픽 문제 2차 수정 ([#69](https://github.com/DTS-NewGRF/DTS/issues/69)) (2026.03.22)
* [버그] 협궤 개량선 도심전기선로 차량기지 눈 그래픽 수정 ([#70](https://github.com/DTS-NewGRF/DTS/issues/70)) (2026.03.22)
* [선로변경] 고무차륜 지하 GUI ([#72](https://github.com/DTS-NewGRF/DTS/issues/72)) (2026.03.22)
* [버그] 3궤조 LIM 차량기지 기본 그래픽 수정 ([#73](https://github.com/DTS-NewGRF/DTS/issues/73)) (2026.03.29)
* [선로변경] 협궤 개량선 선로, 협궤 개량선 전기선로 그래픽 변경 ([#74](https://github.com/DTS-NewGRF/DTS/issues/74)) (2026.03.29)

## 인게임 등록
[1.05] 2026.03.16 <br>
[이슈작업]
* [선로추가] 협궤 개량선 선로 (1067mm) / Narrow gauge Main Tracks (1067mm) ([#53](https://github.com/DTS-NewGRF/DTS/issues/53)) (2026.02.27)
* [선로추가] 협궤 개량선 전기선로 (1067mm) / Narrow gauge Main Tracks (Electrified, 1067mm) ([#54](https://github.com/DTS-NewGRF/DTS/issues/54)) (2026.02.27)
* [선로추가] 협궤 개량선 도심전기선로 (1067mm) / Narrow gauge Main Tracks (Urban, Electrified, 1067mm) ([#55](https://github.com/DTS-NewGRF/DTS/issues/55)) (2026.02.27)
  * [버그] 협궤 개량선 도심전기선로 터널 그래픽의 눈 오버레이 그래픽 문제 ([#58](https://github.com/DTS-NewGRF/DTS/issues/58)) (2026.02.28)
* [버그] 협궤 일반선 선로에서 전기열차가 나옴 ([#56](https://github.com/DTS-NewGRF/DTS/issues/56)) (2026.02.27)
* [버그] 협궤 기존선 도심전기선로 터널 그래픽에 눈 오버레이가 적용되어 있지 않음 ([#59](https://github.com/DTS-NewGRF/DTS/issues/59)) (2026.02.28)
* [선로추가] 듀얼게이지 일반선 선로 (1067mm+1435mm) / Dual gauge Main Tracks (1067mm+1435mm) ([#60](https://github.com/DTS-NewGRF/DTS/issues/60)) (2026.02.28)
* [선로추가] 듀얼게이지 일반선 전기선로 (1067mm+1435mm) / Dual gauge Main Tracks (Electrified, 1067mm+1435mm) ([#61](https://github.com/DTS-NewGRF/DTS/issues/61)) (2026.02.28)
* [버그] 표준궤 지하 도시철도 선로 터널 그래픽이 없음 ([#62](https://github.com/DTS-NewGRF/DTS/issues/62)) (2026.03.05)
* [선로변경] 3궤조 LIM 차량기지 그래픽 변경 ([#64](https://github.com/DTS-NewGRF/DTS/issues/64)) (2026.03.16)
  * [버그] 3궤조 LIM 차량기지 눈 그래픽 문제 ([#67](https://github.com/DTS-NewGRF/DTS/issues/67)) (2026.03.16)
* [선로변경] 3궤조 일반선 차량기지 그래픽 변경 ([#65](https://github.com/DTS-NewGRF/DTS/issues/65)) (2026.03.16)
* [선로변경] 협궤 개량선 도심전기선로 차량기지 그래픽 변경 ([#66](https://github.com/DTS-NewGRF/DTS/issues/66)) (2026.03.16)
  * [버그] 협궤 개량선 도심전기선로 차량기지 그래픽이 어긋나있던 문제 ([#68](https://github.com/DTS-NewGRF/DTS/issues/68)) (2026.03.16)

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
