
{
  "Version": "1.0.0",
  "ReleaseNotes": "",
  "UrlUpdate": "",
  "Sms": "",
  "EmailFeedback": "",
  "UrlContato": "",
  "UrlTermos": "",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"
    }
  ],
  "Servers": [
    {
      "Name": "Servidor BR",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "45.182.161.107",
      "CheckUser": "",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
 
        {
            "Name": "TIM SALDO VALIDO",
            "FLAG": "tim",
            "Payload": "GET / HTTP/1.1[crlf]Host: helpypro.stoodi.com.br[crlf]Expect: 100-continue[crlf][crlf][split][crlf][crlf]PUT- // HTTP/1.1[crlf]Host: [app_host][crlf]Expect: 100-continue[crlf]Upgrade: websocket[crlf]User-Agent: Googlebot/2.1 (+http://www.google.com/bot.html)[crlf][crlf]",
            "SNI": "",
            "TlsIP": "",
            "ProxyIP": "helpypro.stoodi.com.br",
            "ProxyPort": "80",
            "Info": "Proxy" 
            }  ]
}
