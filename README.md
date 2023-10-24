{
		"inbounds": [],
		"outbounds": [
				{
						"mux": {
								"enabled": false
						},
						"protocol": "vmess",
						"settings": {
								"vnext": [
										{
												"address": "server1.edi-kuswanto.com",
												"port": 80,
												"users": [
														{
																"alterId": 0,
																"id": "6cd591e6-533d-4834-8cc9-9f8c89d8f395",
																"level": 8,
																"security": "auto"
														}
												]
										}
								]
						},
						"streamSettings": {
								"network": "ws",
								"security": "none",
								"wsSettings": {
										"headers": {
												"Host": "sg-do1.nexsusvpn.me"
										},
										"path": "/vmess"
								}
						},
						"tag": "VMESS"
				}
		],
		"policy": {
				"levels": {
						"8": {
								"connIdle": 300,
								"downlinkOnly": 1,
								"handshake": 4,
								"uplinkOnly": 1
						}
				}
		}
}
