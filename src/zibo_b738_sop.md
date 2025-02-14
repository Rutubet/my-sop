# Zibo B737-800X SOP
## 冷舱启动
### 平板设置
- [ ] CONFIGURE & CUSTOMIZE -> HARDWARE -> NOSEWHEEL AXIS: ROLL
- [ ] CONFIGURE & CUSTOMIZE -> REALISM -> ALIGN TIME: SHORT
- [ ] CONFIGURE & CUSTOMIZE -> REALISM -> REFULE TIME: SHORT
- [ ] FUEL, WEIGHT & BALANCE -> PAYLOAD 加油
### 顶板设置
- DC -> ON
- EMER EXIT LIGHTS -> 关盖
- NO SMOKING -> AUTO
- FASTEN BELTS -> AUTO
- APU -> ON -> START
- 叫小推车
- 等待APU GEN OFF BUS亮起
- 2 x APU GEN -> ON
- APU BLEED -> ON
- IRS L/R -> NAV
- YAW DAMPER -> ON
- FULE PUMPS -> ON 视情况而定开几个
- HYD PUMPS -> ELFC 1/2 -> ON
- WINDOW HEAT L/R -> SIDE/FWD -> ON
- PROBE HEAT A/B -> ON
- TRIM AIR -> ON
- FLT ALT -> 巡航高度
- LAND ALT -> 目的机场标高ft
### CDU设置
- FMC -> POS INIT：
- - 左二输入起飞机场ICAO
- - NEXT PAGE -> GPS L/R 复制 -> SET IRS POS
- ROUTE:
- - DEST: 目的机场ICAO
- - NEXT PAGE -> 从右一开始输入航路
- - ACTIVATE -> EXEC
- PERF INIT:
- - 左一点一下自动出
- - RESERVERS -> 备用燃油：一般输5
- - COST INDEX -> 一般输50
- - CRZ ALT -> 巡航高度
- - EXEC
- N1 LIMIT:
- - 不用调
- TAKE OFF:
- - FLAPS -> 5
- - CG -> 输入平板加油界面TOW CG
- - 显示TRIM配平，调整轮
- - V1,VR,V2直接照抄
- - QRH -> ON
- 离场程序：
- - CDU -> DEP ARR
- - 根据第一个航路点选择离场程序
- - EXEC
- 进场/进近程序：
- - CDU -> DEP ARR
- - 根据最后一个航路点选择一个RNAV进场程序
- - 根据预计降落跑道选择RNAV ILS进近程序(一般为ILS Z)
- - TRANS -> 查看航图选择IAF点作为TRANS
- - EXEC
### 检查航路
- CDU -> LEGS
- CTR -> PLN, TFC视情况调
- CDU -> STEP> -> 一步一步检查确保没有断点
- 假设有断点：
- - 把断点后一个点复制到断点处进行连接
## 推车
- 指定推出方向
- 等待松刹车指令 -> 松刹车
- 等待启动引擎指令
- 二发: GRD -> 等待N2到达20以上 -> 二发扳手扳上去
- 按同样步骤启动一发
- 引擎供电 -> 关闭APU -> 关闭APU引气
- L/R PACK -> AUTO
- ISOLATION VALVE -> AUTO
- 确认顶板无红灯
- 等待推车到位 -> 打开刹车
- 等待推车离开 -> 松刹车
- 自动驾驶设置:
- - 速度V2以上
- - AUTO BREAK -> RTO
- - 襟翼5度
- - 高度设置成巡航高度
## 滑行
- 滑行到跑道 -> 刹车
## 起飞
- A/T ARM -> ON
- 节流阀推一点，观察两侧推力一致
- 松刹车
- 节流阀推到底
- 400ft点亮CMD
- VNAV/LNAV -> ON
- 收起起落架 -> 起落架三个灯灭了 -> 拉到中间
- AUTO BREAK -> OFF
- 开启TERR
## 进场
- 设置ILS结盟频率（NAV频率）
- 设置磁航向(COURSE)
- AUTO BREAK -> 2
- 扰流板 -> ARMED
- CDU -> INIT REF -> 设置着陆襟翼度数和着陆速度
- 距离下高点20nm时开始下高，下降高度设置为IAF点的高度
- 根据 CDU -> LEGS 设置下降率直至IAF点
## 进近
- IAF之后点亮APP，建立ILS进近
- 点亮两个CMD灯,开启自动降落
## 着陆
- 着陆后开启反推（默认shift + /）
- 关闭自动驾驶
- 降低到一定速度尽快脱离跑道
