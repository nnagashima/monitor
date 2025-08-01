# monitor
KeepAlived + Nginx + VictoriaMetrics
&
Prometheus

- node1をアクティブ側、node2をスタンバイ側として考えてください。
- node側のhostsファイルでkeepalivedのvipを名前解決できるように書いてください。（例：192.168.21.13 vm-vip）　
