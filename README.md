# maikehongg-heroku-joss

{
    "name": "fjsgjhg",
    "description": "DaoChen's v2", 
    "keywords": [
      ""
    ],
      
    "env": {
       "PROTOCOL": {
         "description": "协议VMess或VLESS,请填小写的vmess或vless",
         "value": "vmess",
         "required": true 
        },

      "UUID": {
        "description": "用户的主ID",
        "value": "", 
        "required": false 
        },
      
      "WS_PATH": {
        "description": "websocket路径",
        "value": "/ray",
        "required": true
        }
    },
    "website": "",
    "repository": "",
    "stack": "container",
    "features": [ 
        "runtime-dyno-metadata"
    ]
  }
  //--------------------------------------------------



;   {
;     "name": "abcd_fan",
;     "description": "",
;     "keywords": ["vmess vless trojan shadowsocks socks"],
;     "env": {
;         "AA": {
;             "description": "初阶用户只需修改以下AUUID点击页面最后的Deploy app按钮即可开始部署",
;             "value": "如出现错误，请检查参数格式或多尝试几次。使用自定义参数请务必先充分理解其含义"
;         },
;         "AUUID": {
;             "description": "UUID充当各个配置的路径和账号密码，建议修改和妥善保存,可生成UUID的网站: https://www.uuidgenerator.net",
;             "value": "8f91b6a0-e8ee-11ea-adc1-0242ac120002"
;         },
;         "CADDYIndexPage": {
;             "description": "自定义CADDY部署完成后点击View的显示页面，参考readme.md中的（5：Caddy主页配置）",
;             "value": "https://raw.githubusercontent.com/caddyserver/dist/master/welcome/index.html"
;         },
;         "ParameterSSENCYPT": {
;             "description": "SS加密方式，查看支持协议: https://www.v2fly.org/config/protocols/shadowsocks.html",
;             "value": "chacha20-ietf-poly1305"
;         }
;     },
;     "repository": "",
;     "stack": "container"
; }
