# PORTABLEAPPK
PORTABLEAPPK便携签到-pushplus推送日志

# 使用教程
  1、打开青龙面板，脚本管理-》新建空文件夹（文件名portableappk，父目录为空）-》新建空文件（文件名main.py，父目录portableappk)
  
  2、依赖管理-》添加python依赖（requests ddddocr json os）
  
  3、定时任务-》添加任务（命令：	/ql/data/scripts/portableappk/main.py 定时规则：0 9 * * *）
  
  4、环境变量-》新建变量（新建三个变量，名称为：PORTABLEAPPK_USER、PORTABLEAPPK_PASSWD、DINGTALK_TOKEN，对应分别为邮箱、密码、钉钉推送token）
  
  5、定时任务-》执行（查看日志是否成功）

  补充：需要pushplus推送 直接在源代码中添加pushplus_token即可

