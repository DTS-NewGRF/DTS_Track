# Diversity Track Set 다양성 선로세트 /DTS_Track
![DTS_Track_board](https://github.com/DTS-NewGRF/DTS_Track/blob/main/docs/DTS_Track_board.png)
**다양성 선로세트**는 <br>
2024년 3월 28일 DTS 오브젝트 차량기지를 호환하기 위해 제작되었습니다.<br>

[Github release 페이지](https://github.com/DTS-NewGRF/DTS_Track/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
[1.03] 2026.01.24 <br>
[이슈외 작업]
* [변경] 기존선 도시철도 차량기지 그래픽 오류 수정
* [2025.09.13] DTS 열차셋의 오브젝트, 경유지 추가 적용.

[이슈작업]
* [선로변경] 고무차륜 선로 호환되는 선로 추가 ([#17](https://github.com/DTS-NewGRF/DTS/issues/17)) (2025.09.03)
* [선로변경] 과좌식 모노레일 선로 호환되는 선로 추가 ([#18](https://github.com/DTS-NewGRF/DTS/issues/18)) (2025.09.03)
* [선로변경] 3궤조 선로 그래픽 변경 ([#20](https://github.com/DTS-NewGRF/DTS/issues/20)) (2026.01.10)
* [선로변경] LIM 3궤조 그래픽 변경 ([#21](https://github.com/DTS-NewGRF/DTS/issues/21)) (2026.01.10)
* [선로추가] 도시철도(지하) 선로 / Electric metro track (Underground) ([#22](https://github.com/DTS-NewGRF/DTS/issues/22)) (2026.01.10)
  * [버그] 지하 선로의 그래픽 문제 ([#25](https://github.com/DTS-NewGRF/DTS/issues/25)) (2026.01.10)
  * [버그] 지하 선로의 그래픽 문제 (2) ([#26](https://github.com/DTS-NewGRF/DTS/issues/26)) (2026.01.23)
* [선로추가] 콘크리드 장식 / Concrete Deco ([#23](https://github.com/DTS-NewGRF/DTS/issues/23)) (2026.01.10)
* [선로추가] 도시철도 3궤조 (지하) / Electric metro track (Underground Third rail current collector) ([#24](https://github.com/DTS-NewGRF/DTS/issues/24)) (2026.01.10)
  * [버그] 지하 선로의 그래픽 문제 ([#25](https://github.com/DTS-NewGRF/DTS/issues/25)) (2026.01.10)
  * [버그] 지하 선로의 그래픽 문제 (2) ([#26](https://github.com/DTS-NewGRF/DTS/issues/26)) (2026.01.23)
* [선로변경] 노반 터널, 다리 그래픽 추가 ([#27](https://github.com/DTS-NewGRF/DTS/issues/27)) (2026.01.23)
* [선로추가] 노반 (지하) / RailBed (Underground) ([#28](https://github.com/DTS-NewGRF/DTS/issues/28)) (2026.01.23)
* [선로변경] 고무차륜 선로 그래픽 변경 ([#30](https://github.com/DTS-NewGRF/DTS/issues/30)) (2026.01.24)
* [선로변경] 지하선로 Catenary ([#35](https://github.com/DTS-NewGRF/DTS/issues/35)) (2026.01.24)
* [선로추가] 지하선로 울타리 ([#36](https://github.com/DTS-NewGRF/DTS/issues/36)) (2026.01.24)
* [선로변경] 노반 GUI 변경 ([#37](https://github.com/DTS-NewGRF/DTS/issues/37)) (2026.01.24)

[변경]
* 기존선 도시철도 차량기지 그래픽 오류 수정

## 인게임 등록
```
[1.02] 2025.02.02
[추가]
- 고속선 430, 600 속도고정 선로 추가
```

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
