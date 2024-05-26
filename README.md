<h3 align = "center">
  Im Youssef Mohamed
</h3>

<img align="center" src="https://cdn.dribbble.com/users/1059583/screenshots/4171367/media/34e69eb61a7bd8dea1c957a8b82605a7.gif" alt="coding gif">

<h4>
  <bold>
    • Currently Learning C++
  </bold>
</h4>




{
  "inbounds": [
    {
      "port": 1080,
      "listen": "127.0.0.1",
      "protocol": "socks",
      "settings": {
        "auth": "noauth",
        "udp": true,
        "ip": "127.0.0.1"
      }
    }
  ],
  "outbounds": [
    {
      "protocol": "vmess",
      "settings": {
        "vnext": [
          {
            "address": "de2.v2vmess.site",
            "port": 443,
            "users": [
              {
                "id": "ae668f89-74eb-4d2c-b041-1d65163c3a80",
                "alterId": 0,
                "security": "auto"
              }
            ]
          }
        ]
      },
      "streamSettings": {
        "network": "ws",
        "security": "tls",
        "tlsSettings": {
          "allowInsecure": true,
          "serverName": "playstation.net"
        },
        "wsSettings": {
          "path": "\/vmess",
          "headers": {
            "Host": "playstation.net"
          }
        }
      }
    }
  ],
  "policy": {
    "levels": {
      "0": {
        "connIdle": 300,
        "downlinkOnly": 0,
        "handshake": 4,
        "uplinkOnly": 0
      }
    }
  }
}
