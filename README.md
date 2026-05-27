# QR-series
This is QR series (ex. GPT QR, WIKI QR)

I create QR codes wiith python's qrcode library👇🏼


import qrcode

url = 'chatgpt.am'

qr = qrcode.make(url)

qr.save("/storage/emulated/0/Download/chatgpt-qr.png")