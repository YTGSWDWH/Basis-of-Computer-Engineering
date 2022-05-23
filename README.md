# Basis-of-Computer-Engineering
## 一、浮点数与定点数
* **浮点数：小数点的位置是浮动的，小数点的位置由阶码规定**。
    * 浮点数N可分成阶码和尾数两部分来表示，其中尾数是个规格化的纯小数，N = 尾数 x 基数^阶码
    * 例如，假设16位虚拟机中，阶码占5位，尾数占9位，数符、阶符各占一位。实数28.625的浮点数表示为N = (11100.101)<sub>2</sub> = (0.11100101) x 2<sup>101</sup>,该数在16位虚拟机中的浮点数表示如下表所示，其中整数部分是前面补零值不变，小数部分是后面补零值不变。
    * 0|0|00101|111001010
      ---|---|---|---

* **定点数：小数点的位置是固定不变的**
    * 定点小数：用来表示纯小数
    * 定点整数：用来表示纯整数
