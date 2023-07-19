# PuzzleSolver
一款针对CTF竞赛MISC的工具~

# Q&A

Q：

```
[*] cloacked-pixel执行失败!

Traceback (most recent call last):
File "core\ErrorCore\errorCore.py", line 13, in wrapper
File "core\BruteForce\Cloacked_Pixel_Func\cloacked_pixel.py", line 75, in BruteForceLSB
File "magic\magic.py", line 71, in __init__
File "magic\magic.py", line 272, in magic_load
File "magic\magic.py", line 203, in errorcheck_negative_one
magic.magic.MagicException: b'could not find any valid magic files!'
```

A：

```
最简单的解决方案，换个目录就好了（原因是目录存在了中文）
可能有些朋友说我放在桌面为什么还出现这个问题？（因为你用户名是中文）
存放入C\D\E\F等盘都行，简而言之不要有中文!
```

