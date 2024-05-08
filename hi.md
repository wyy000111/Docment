{
  "outbounds": [
    {
      "type": "vmess",
      "tag": "Replit § 0",
      "server": "localhost",
      "server_port": 443,
      "uuid": "9fc469f0-1c3b-4517-a3be-28b83f8d93c6",
      "security": "auto",
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "localhost",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/vm",
        "headers": {
          "Host": "localhost"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },

    {
      "type": "vmess",
      "tag": "MW-US3 § 2",
      "server": "us3.apinew.com",
      "server_port": 443,
      "uuid": "8626e9b1-f061-4dcb-928e-fb0c0c397c65",
      "security": "auto",
      "alter_id": 233,
      "authenticated_length": true,
      "tls": {
        "enabled": true,
        "server_name": "us3.apinew.com",
        "utls": {
          "enabled": true,
          "fingerprint": "chrome"
        }
      },
      "transport": {
        "type": "ws",
        "path": "/233blog",
        "headers": {
          "Host": "us3.apinew.com"
        },
        "early_data_header_name": "Sec-WebSocket-Protocol"
      }
    },
    {
      "type": "vless",
      "tag": "CF § 3",
      "server": "www.visa.com.sg",
      "server_port": 8880,
      "uuid": "04c793d1-5450-40b5-8201-dd59dacad064",
      "transport": {
        "type": "ws",
        "path": "/",
        "headers": {
          "Host": "v2ray.wyy000111.workers.dev"
        },
        "max_early_data": 2048,
        "early_data_header_name": "Sec-WebSocket-Protocol"
      },
      "packet_encoding": ""
    },
    {
      "type": "vmess",
      "tag": "Azure-US § 4",
      "server": "52.160.33.186",
      "server_port": 300,
      "uuid": "cd07081b-2e52-4ebf-8ee6-6ca16175c7f2",
      "security": "auto",
      "authenticated_length": true
    },
    {
      "type": "vmess",
      "tag": "Azure-JP § 5",
      "server": "172.207.41.121",
      "server_port": 250,
      "uuid": "72b9088f-51e3-49af-90f3-4a0e34a2a262",
      "security": "auto",
      "authenticated_length": true
    },
  ]
}
