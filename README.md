# 使用VPS 架設VPN
## AWS lightsail
* 基本環境
  * Ubuntu 20.04


* Server設定
  *
  ```shell
  sudo apt update
  sudo apt upgrade

  # 使用 Install.sh 安裝
  # source https://github.com/Nyr/openvpn-install

  sudo systemctl status openvpn-server@server.service

  # openvpn client 連線方式
  # 安裝 openvpn client
  # sudo openvpn --config *.ovpn

  ```