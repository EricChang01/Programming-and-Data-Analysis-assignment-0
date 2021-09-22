# Zen of Python

> Special cases aren't special enough to break the rules.

> Errors should never pass silently.

> In the face of ambiguity, refuse the temptation to guess.

這三句簡短的描述了寫程式最容易忽略的問題-邊界情況，這些邊界情況常常是造成程式出錯的主因，而在測試時卻會因為這類情況比較不容易想到而忽略，讓人以為程式已經寫對了但其實不然。

出現這種邊界情況導致的bug時，直覺上會想特別判斷這些情況，但這通常不是最好的寫法，仔細分析後大都可以找到個既能解決原本的問題，又能讓這些邊界條件不會出錯的方式。

最後，要避免忽略邊界條件，解決之道是在閱讀問題時更全面地分析各種情況，避免一些模糊地帶，而不是認為一般的case會對，其他的就會對。

綜合以上原因，我相當喜歡 Python 禪學中的這幾句話。
