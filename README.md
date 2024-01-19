# 三相逆变器驱动板
## 1.设计指标
- 输入电压：24V-48V DC
- 输出电压：24V(RMS) AC
- 频率：50-60Hz
- 输出功率：60W
- 额定电流：10A

## 2.附加接口
- 一路5V-1A输出
- 输入电压分压采样输出
- 输出电压分压采样输出（加偏置）
- 三相桥低侧电流采样放大输出（加偏置）
- 带光耦隔离的三相PWM信号输入

## 3.元件选型
- 偏置电源：LP3985
- MOSFET：NCEP023N10 100V 300A
- 三相桥驱动器：eg2133
- 12V电源芯片：eg1198
- 5V电源芯片：ln3492
- 光耦：PC817