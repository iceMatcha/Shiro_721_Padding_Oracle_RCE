# Shiro-721 Padding Oracle RCE Exp
- 纯手工实现Padding Oracle过程, 没有利用python-paddingoracle的api，可用于学习padding oracle细节。
- 默认采用jrmp gadget, 可以在脚本中自行更换，但是不建议，除非目标环境需要，因为padding oracle的耗时依赖于待加密payload的长度，jrmp长度相对较短。
- 测试环境：官方demo就可以了。
- 参考链接：https://blog.skullsecurity.org/2016/going-the-other-way-with-padding-oracles-encrypting-arbitrary-data
- Usage:
  - python3 shiro_oracle_padding.py <target_url> <regular_cookie>
