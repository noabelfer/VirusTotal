# VirusTotal
Based on VirusTotal api, This program lets you check for URL reputation 


# Prerequisites
api key from https://www.virustotal.com/

# arguments 
-s --scan: optional argument, scans the url for an updated analize
-k --apikey: VT apikey

# example
noa@MacBook-Air-3 % ./main.py https://www.amazon.com/ https://www.ebay.com/ https://www.ynet.co.il/home/0,7340,L-8,00.html -k *****apikey*****
['https://www.amazon.com/', 'https://www.ebay.com/', 'https://www.ynet.co.il/home/0,7340,L-8,00.html'] 32cdd325e88f9126cf3fb455b301c3c17761e9b6c4c1fa4577255cedf069b74d False
urls: ['https://www.amazon.com/', 'https://www.ebay.com/', 'https://www.ynet.co.il/home/0,7340,L-8,00.html'] toscan: False
saving to cache
{'url': 'https://www.amazon.com/', 'reputation': 98, 'time': 1673870233, 'time_analyze': '2023-01-16 13:57:13'}
saving to cache
{'url': 'https://www.ebay.com/', 'reputation': 27, 'time': 1673857274, 'time_analyze': '2023-01-16 10:21:14'}
saving to cache
{'url': 'https://www.ynet.co.il/home/0,7340,L-8,00.html', 'reputation': -1, 'time': 1673735148, 'time_analyze': '2023-01-15 00:25:48'}

