# HackALU 的設計原理

![[圖，HackALU 的操作表]](HackALU.png)

獎金題：請證明 y-x = !(x+!y) ，本題第一位答出者加學期總成績十分。

陳盈翰同學給出證明如下：

```
引理： -x = !x + 1 
定理： !x = -x-1

證明：!(x+!y) 
= -(x+!y)-1
= -(x+(-y-1))-1
= - (x-y-1)-1
= -x+y
= y-x
```