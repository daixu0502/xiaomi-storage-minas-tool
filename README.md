小米智能存储

已不能使用 mitee_tool rpmb set ssh_en true 固化开机SSH

使用以下脚本设置开机启动

#install-ssh-autostart-fix.sh

用法：

  bash install-ssh-autostart-fix.sh [小米智能存储IP]

示例：

  bash install-ssh-autostart-fix.sh 10.31.0.66

请先运行开启 SSH 的脚本，确认可以使用 root 密钥登录设备。
脚本不会重启设备；开机后约 40 秒 SSH 会恢复。
