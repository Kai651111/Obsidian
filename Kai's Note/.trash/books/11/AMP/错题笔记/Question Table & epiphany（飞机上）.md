# Question Table & Epiphany

## Questions
- 直接向气体放电 Electrical Discharge 会发生什么
- 为什么 diode laser 会：
	- 高效率
	- better match between the output of the spectrum
- 波的干涉是波的叠加吗
- 泛音与谐波的关系
***
## Epiphany
### 激光链路
- Population inversion 粒子数反转（用 pumping 产生，根据不同的 medium）
	- Medium 分类
		- Solid
			- 常用：半导体激光器（好）和灯
		- CO₂
			- 常用：放电
		- 半导体
			- 本质上也是放电
	- Pumping不会把所有的能量转化为激光的能量，跟不同的medium有关。这个叫**wall plug efficiency**，**插墙效率**。
		- 插墙效率较高的source：
			- 光纤激光器
			- 二极管激光器
- Stimulated emission（受激辐射）
	- Pumping 开始就发生
- Amplification
	- 多次受激辐射（不同的optical resonator，total 和 partial reflector）
---
### 光束与准直
- Collimation
	- 只是在 Gaussian beam 下研究的课题

- BPP and M²
	- 虽然里面有 r_g
	- 但 r_g 是所有光束通用的 beam waist
		- Gaussian beam 和 general beam 的 r_g 相同

- Beam 半径关系
			$$r₀（标准差）< r_g < r_r$$
	- 为什么激光功率通常是86.5%的：因为在beam waist以内的激光的强度beam intensity时86.5%。
    	- 记住，这只是gaussian beam的参数
---
### Beam quality factor
- M²
	- 用发散角量化
	- 与 Gaussian beam 发散角的 ratio
- BPP
	- 用发散角和 beam waist量化
	- 普通激光和高斯激光的 r_g 一样
	- 多了一个 beam waist 宽度

---
### Pulse
- CW 和 PW
- PW
	- 参数
		- 时间有关的参数
			- $f_p$：pulse frequency (PRR（pulse repetition rate）) 脉冲周期的倒数
			- τ：pulse duration
			- FWHM：full width at half maximum
			- $t_{tot}$：pulse period
		- pw功率定义
			- Peak power
			- Average pulse power（脉冲时间内）
			- Average power（脉冲周期内）
			- Duty cycle
	- pulse duration（脉冲时间，不是脉冲周期）
		- 时间尺度
			- s
			- ms（10⁻³）
			- µs（10⁻⁶）
			- ns（10⁻⁹）
			- ps（10⁻¹²）
			- fs（10⁻¹⁵）
		- 时间越短，越适合精确的 micromachining
#### 根据pulse frequency（脉冲周期的倒数）而产生的temporal profile的分类：
- Free running（10⁻³ ～ 10⁻⁴） ms 和 µs
	- 取决于 pumping

- Q-switch（10⁻⁹，ns）
	- Q开关性质
		- q开关 在 resonator 里
		- medium 饱和后，才可以发射（Q开关）
		- 有主动被动之分
	- 主动 Q-switch
		- 光学机械器件
		- 快门、旋转反射镜
		- Q 值突破阈值即可发射
	- 被动 Q-switch
		- 可饱和吸收器（saturable absorber）
		- 光强超过阈值后透过率突然增加
- Mode locking（10⁻¹² ～ 10⁻¹⁵）
	- ps皮秒 和 fs
	- 锁模
	- 主要由于波的干涉（interference）

---
### Laser sources 感知
- 光线激光和二极管激光的efficiency很高（上面说的穿墙效应）
- 二氧化碳激光不能fiber，但是波长最长，高功率下的m2还可以。
- fiber 激光 YbGlass不能 反射
- 光线激光的功率非常高，而且高功率下的m2也还可以。
- 二极管激光和NdYAG激光 在高功率下，m2不太行。
- 加工金属的A Aborbtion rate近似100%

### 不同材料对于不同激光的吸收不一样
- 二氧化碳激光波长太长，对non metal material有利（有机材料）
- 金属：高功率的光纤激光
- 3倍（2倍也行）频率倍增的NdYAG：金属吸收率更好。
- UV 的吸收率更好：但是kw级的UV不可用。
- 只能是个指导性的参考（那两条曲线）因为还有别的影响因素。
- 通常用PW运行，用于micro machining
---
## Unimportant
- 激光特性
	- Monochromaticity
	- Coherence
	- Collimation
