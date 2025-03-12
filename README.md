使用Actions配合frp内网穿透部署自己的v2ray


一、添加token到变量

Settings→Secrets and variables→Actions→New repository secret

变量名：

FRP_USER


二、修改工作流代码中最后一行代码，-p选项后的数字为自己的frp隧道id

三、运行工作流
