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
																								"address": "de3.v2vmess.site",
																								"port": 443,
																								"users": [
																												{
																																"id": "632bc512-8d0e-4289-b2f7-d44953e2d3fb",
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
																				"path": "/vmess",
																				"headers": {
																								"Host": "de3.v2vmess.site"
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
