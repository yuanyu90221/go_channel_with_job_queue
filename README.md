# go_channel_with_job_queue

## introduction

如果遇到同時多個task 輸入

需要放入queue來 等待 work處理

則可以使用go channel 來實做job queue

## topics to discuss

1 如何graceful shutdown當 channel 內沒有job時
