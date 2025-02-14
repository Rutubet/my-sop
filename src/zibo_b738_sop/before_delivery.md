# 放行前检查单
## 平板设置
- [ ] NOSEWHEEL AXIS: ROLL
- [ ] ALIGN TIME: SHORT
- [ ] REFULE TIME: SHORT
- [ ] 油量设置成Block Fuel
## 顶板设置
- [ ] DC -> 关盖
- [ ] EMER EXIT LIGHTS -> 关盖
- [ ] NO SMOKING -> AUTO
- [ ] FASTEN BELTS -> AUTO
- [ ] APU -> ON -> START
- [ ] 连接推车
- [ ] 调整频率至放行
- [ ] 等待APU GEN OFF BUS亮起
- [ ] 2 x APU GEN -> ON
- [ ] APU BLEED -> ON
- [ ] IRS L/R -> NAV
- [ ] YAW DAMPER -> ON
- [ ] FULE PUMPS -> ON 视情况而定开几个
- [ ] HYD PUMPS -> ELFC 1/2 -> ON
- [ ] WINDOW HEAT L/R -> SIDE/FWD -> ON
- [ ] PROBE HEAT A/B -> ON
- [ ] TRIM AIR -> ON
- [ ] FLT ALT -> 巡航高度ft
- [ ] LAND ALT -> 到达机场标高ft (Little Navmap Overview)
## CDU设置
### FMC -> POS INIT：
- [ ] 左二输入起飞机场ICAO
- [ ] NEXT PAGE -> GPS L/R 复制 -> SET IRS POS
### ROUTE:
- [ ] CO ROUTE: 飞行计划文件名
- [ ] ACTIVATE -> EXEC
### PERF INIT:
- [ ] 左一点一下自动出
- [ ] RESERVERS -> 5
- [ ] COST INDEX -> 50
- [ ] CRZ ALT -> 巡航高度ft
- [ ] EXEC
### N1 LIMIT:
Skip
### TAKE OFF:
- [ ] FLAPS -> 5
- [ ] CG -> 输入平板加油界面TOW CG
- [ ] 调整配平轮至TRIM显示数值
- [ ] 设定V1,VR,V2
- [ ] QRH -> ON
## 检查航路
- CDU -> LEGS
- CTR -> PLN, TFC视情况调
- [ ] CDU -> STEP> -> 一步一步检查确保没有断点
## 申请放行
- [ ] 抄收ATIS通波
> ATIS C 17L & 17R 1026 120.3
- [ ] 设置修正海压
- [ ] [A-CDM 设置TOBT](https://vacdm.vatprc.net/) 
- [ ] 向管制申请放行
> CSZ8902 502
- [ ] 抄收放行信息
> 17L SAS81D 900 2372
- [ ] 设置应答机
- [ ] 设置起始高度
- [ ] 设置离场程序



### 1


- 进场/进近程序：
- - CDU -> DEP ARR
- - 根据最后一个航路点选择一个RNAV进场程序
- - 根据预计降落跑道选择RNAV ILS进近程序(一般为ILS Z)
- - TRANS -> 查看航图选择IAF点作为TRANS
- - EXEC
