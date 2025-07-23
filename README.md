# GasMask
* packformat: 7, 10/ versions 1.17 ~ 1.17.1, 1.19 ~ 1.19.3

방독면을 제작할 수 있으며, 지상 지역이 점차 위험 지역으로 변합니다.
해당 위험 지역은 방독면 이용 시 피해를 막을 수 있습니다.

가죽 모자, 유리판, 철괴, 흰 양털, 목탄, 종이를 이용해 방독면을 제작할 수 있습니다.

변경 사항
1. 옵션명을 변경하였습니다.  
* erodedHeight > harzardY, maxErodedHeight > harzardLimitY, erodingMin > harzardMinInterval

- 지원하는 명령어를 확인합니다.
`/function gasmask:config`
- 현재 위험지역 높이를 설정합니다.
`/scoreboard players set harzardY config <amount>`
- 지하와 지상을 구분 시킬 위험지역 범위 한계선을 지정합니다.
`/scoreboard players set harzardLimitY config <amount>`
- 위험지역이 확장되는 시간 간격을 설정합니다(분).
`/scoreboard players set harzardMinInterval config <amount>`
