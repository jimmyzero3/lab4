Question A:

00000000004005c0 T main
0000000000400594 T _Z7averageif
0000000000400566 T _Z7averagePdRd

Question B:

output:
	1	8
	4	8
	4	8
	8	8
此輸出結果代表
char型別的變數佔了1單位的記憶體空間(實際bit大小似乎與作業系統有關)
int及float型別佔4倍char大小、double及pointer型別8倍。

而pointer因為儲存的是記憶體位址，故不論是什麼型別的pointer，大小都是一樣的。
