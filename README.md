# html2emoji
Convert HTML escape sequence to emoji with explanation (Chinese/English). 

将HTML中的Emoji转义序列转换成Unicode形式，并可转换成其中英文含义。

# Usage
    \>\>\> import html2emoji
    \>\>\> emj = html2emoji.html('&# xd83c;&# xdf82;')
    \>\>\> print(emj.show)
    '🎂'
    \>\>\> print(emj.meanc)
    ['庆祝', '生日', '蛋糕', '慶祝', '生日蛋糕']
    \>\>\> print(emj.meanc[0])
    '庆祝'
    \>\>\> print(emj.meane)
    'birthday_cake'
