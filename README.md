# Airplane-Sleep (macOS Catalina and Mojave)
Disable wifi and bluetooth when closing your MacBook or putting it to sleep! (Tested in 2023, Ventura 13.3.1)

1. Copy `.sleep` and `.wakeup` into your home folder aka `~/`
2. Make them executable `chmod +x ~/.sleep` and `chmod +x ~/.wakeup`
3. Install `brew install sleepwatcher blueutil`
4. Run `brew services start sleepwatcher`
5. Test it
6. Success 🚀 