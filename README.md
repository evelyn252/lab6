# lab6
实验六中主要理解两个main函数的作用

1、without——metircs_main.go 只有/abc路由，因此无法完成计数功能，监听5565端口，返回相应的数据信息。

2、metrics_version_main.go 加入/metrics路由，因此当访问/metrics时，返回拉取到的metrics的总数，即完成了计数，显示在request_total中。
