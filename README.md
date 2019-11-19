# Shiro-721 Padding Oracle RCE Exp
- 纯手工实现Padding Oracle过程, 可用于学习padding oracle细节。
- 默认采用jrmp gadget, 可以在脚本中自行更换。
- 测试环境：官方demo就可以了。
- 参考链接：https://blog.skullsecurity.org/2016/going-the-other-way-with-padding-oracles-encrypting-arbitrary-data
- Usage:
  - python3 shiro_oracle_padding.py <target_url> <regular_cookie>
