# 期中總整理

### 第一週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [Not](https://github.com/Rafu2102/_co/blob/master/01/Not.hdl)
* [And](https://github.com/Rafu2102/_co/blob/master/01/And.hdl)
* [Or](https://github.com/Rafu2102/_co/blob/master/01/Or.hdl)
* [Xor](https://github.com/Rafu2102/_co/blob/master/01/Xor.hdl)
* [Mux](https://github.com/Rafu2102/_co/blob/master/01/Mux.hdl)
* [Dmux](https://github.com/Rafu2102/_co/blob/master/01/DMux.hdl)

--重點:
利用 NAND（全能閘）構建基本邏輯閘。
理解 NOT, AND, OR, XOR 的邏輯功能與真值表。

### 第二週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [Not16](https://github.com/Rafu2102/_co/blob/master/01/Not16.hdl)
* [And16](https://github.com/Rafu2102/_co/blob/master/01/And16.hdl)
* [Or16](https://github.com/Rafu2102/_co/blob/master/01/Or16.hdl)
* [Mux16](https://github.com/Rafu2102/_co/blob/master/01/Mux16.hdl)
* [Or8Way](https://github.com/Rafu2102/_co/blob/master/01/Or8Way.hdl)
* [Mux4Way16](https://github.com/Rafu2102/_co/blob/master/01/Mux4Way16.hdl)
* [Mux8Way16](https://github.com/Rafu2102/_co/blob/master/01/Mux8Way16.hdl)
* [DMux4Way](https://github.com/Rafu2102/_co/blob/master/01/DMux4Way.hdl)
* [DMux8Way](https://github.com/Rafu2102/_co/blob/master/01/DMux8Way.hdl)

--重點:
使用基本邏輯閘構建 16 位元（Not16, And16, Or16）。
學習多路器（Mux, Mux16, Mux4Way16, Mux8Way16）和分路器（DMux, DMux4Way, DMux8Way）。
Or8Way 用於檢查 8 個位元中是否至少有一個為 1。

### 第三週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [HalfAdder](https://github.com/Rafu2102/_co/blob/master/02/HalfAdder.hdl)
* [FullAdder](https://github.com/Rafu2102/_co/blob/master/02/FullAdder.hdl)
* [Add16](https://github.com/Rafu2102/_co/blob/master/02/Add16.hdl)
* [Inc16](https://github.com/Rafu2102/_co/blob/master/02/Inc16.hdl)

--重點:
構建 HalfAdder 和 FullAdder，理解進位邏輯。
Add16 和 Inc16 處理多位元加法。

### 第四週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [ALU](https://github.com/Rafu2102/_co/blob/master/02/ALU.hdl)

--重點:
ALU 是計算機的核心，結合邏輯運算與算術運算。
實作需要考慮兩個輸入、控制信號（如零化、否定）和輸出（結果與旗標）。

### 第五週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [Bit](https://github.com/Rafu2102/_co/blob/master/03/a/Bit.hdl)
* [Register](https://github.com/Rafu2102/_co/blob/master/03/a/Register.hdl)
* [RAM8](https://github.com/Rafu2102/_co/blob/master/03/a/RAM8.hdl)
* [RAM64](https://github.com/Rafu2102/_co/blob/master/03/a/RAM64.hdl)

--重點:
構建單位元（Bit）和暫存器（Register），學習如何保存狀態。
擴展到 RAM8 和 RAM64，掌握記憶體的分層結構。

### 第六週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [RAM512](https://github.com/Rafu2102/_co/blob/master/03/b/RAM512.hdl)
* [RAM4K](https://github.com/Rafu2102/_co/blob/master/03/b/RAM4K.hdl)
* [RAM16K](https://github.com/Rafu2102/_co/blob/master/03/b/RAM16K.hdl)
* [PC](https://github.com/Rafu2102/_co/blob/master/03/a/PC.hdl)

--重點:
延伸至更大容量的記憶體：RAM512、RAM4K、RAM16K。
實作程序計數器（PC）以追蹤指令執行位置。

### 第七週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [mult](https://github.com/Rafu2102/_co/blob/master/04/mult/mult.asm)

--重點:
使用 Hack 平台的組合語言實現多位元乘法運算（mult.asm）。
學習如何結合 ALU 進行運算邏輯分解。

### 第八週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [Fill](https://github.com/Rafu2102/_co/blob/master/04/fill/Fill.asm)

--重點:
實作簡單的圖形填充程式（Fill.asm）。
學會處理 Hack 平台的鍵盤輸入與螢幕輸出。


### 第九週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [CPU](https://github.com/Rafu2102/_co/blob/master/05/CPU.hdl)

--重點:
建構 CPU，整合控制單元與 ALU。
學會如何執行指令並控制資料流。


### 第十週題目

看老師上課講解和nand2tetris解釋，不會的跑去問ChatGpt。

* [Memory](https://github.com/Rafu2102/_co/blob/master/05/Memory.hdl)
* [Computer](https://github.com/Rafu2102/_co/blob/master/05/Computer.hdl)

--重點:
整合 Memory 與 CPU 成為完整的計算機（Computer.hdl）。
驗證計算機的執行能力，能運行 Hack 平台的程式。
