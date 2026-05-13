# Proxy List

این فایل توسط workflow شماره ۵ ساخته شده است.

> مقدار `ping_ms` زمان رفت‌وبرگشت یک درخواست HTTP/HTTPS از داخل GitHub Actions از مسیر همان proxy است؛ ICMP ping نیست.

## Fastest proxies

| Rank | PROXY_SERVER | PROXY_USERNAME | PROXY_PASSWORD | ping_ms | protocol | status | observed_ip | source |
|---:|---|---|---|---:|---|---:|---|---|
| 1 | `http://209.97.150.167:3128` | `` | `` | 117 | `http` | 200 | `209.97.150.167` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 2 | `http://174.138.174.139:8001` | `` | `` | 669 | `http` | 200 | `173.184.163.120` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 3 | `http://45.59.122.132:80` | `` | `` | 669 | `http` | 200 | `45.59.122.132` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 4 | `http://87.120.205.164:444` | `` | `` | 673 | `http` | 200 | `87.120.205.164` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 5 | `http://174.138.168.74:8001` | `` | `` | 820 | `http` | 200 | `86.48.15.183` | `https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt` |
| 6 | `http://62.113.119.14:8080` | `` | `` | 841 | `http` | 200 | `62.113.119.14` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |
| 7 | `http://65.108.203.37:18080` | `` | `` | 857 | `http` | 200 | `77.111.247.84` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 8 | `http://174.138.174.170:8001` | `` | `` | 904 | `http` | 200 | `206.45.68.23` | `https://free-proxy-list.net/` |
| 9 | `http://181.13.221.155:999` | `` | `` | 1058 | `http` | 200 | `181.13.221.154` | `https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt` |
| 10 | `http://65.108.203.37:28080` | `` | `` | 1104 | `http` | 200 | `77.111.246.14` | `https://raw.githubusercontent.com/proxifly/free-proxy-list/main/proxies/proto...` |

## استفاده در workflow شماره ۴

در workflow `🌐 4-Browse the Web` مقدار `proxy_mode` را روی `fastest-from-file` بگذارید تا ردیف اول همین فایل استفاده شود. برای انتخاب ردیف دیگر، `proxy_mode=rank-from-file` و `proxy_list_rank` را برابر شماره ردیف جدول بگذارید.

فایل ماشینی متناظر: `proxy-list.json`
