# avy-huma
用来在Emacs里使用虎码的编码来跳转到汉字。

基于Ace-pinyin和Avy。

使用方法：

安装Avy，ace-pinyin后安装avy-huma
```lisp
(quelpa '(avy-huma :repo "Dasein1998/avy-huma" :fetcher github)) ;;使用qulepa安装avy-huma
```

然后在ace-pinyin中(require 'avy-huma)就行。

```lisp
(use-package ace-pinyin
  :ensure t
  :config
  (require 'avy-huma)
  (ace-pinyin-global-mode 1)
)
```


参考：
https://emacs-china.org/t/ace-pinyin/15926
