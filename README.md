### 新手入门

参看 [Flink开发文档](http://gitlab.dev.zhaopin.com/DataPlatform/java-D-flink-realtime/blob/peng.rui/src/file/Flink%E5%BC%80%E5%8F%91%E6%8C%87%E5%8D%97V1.3.pdf)
### 建议: <br> 
1、 如果有一个项目包含很多个作业的时候，可以单独建一个package，把相关任务放到里面。	 
2、 把每个过程处理放到一个单独的class里面，这样更好把握整体的逻辑，流程清晰明了。	 
3、 可以将自己的作业提交命令放到resource资源目录下flink-start-command.yml里面，便于作业挂掉的时候，别的同事帮忙处理。
