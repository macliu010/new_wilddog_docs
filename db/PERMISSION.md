# 读写权限


一般来说，我们可以将数据库分成 公有数据 和 基于用户的数据 。 公有数据 是任何人都可以访问的，例如新闻类的APP。基于用户的数据 需要用户认证，例如SNS。

野狗对 实时数据库 的读写权限设置是通过由野狗定义的 规则表达式 来进行的。规则表达式 可以在发生数据变动时进行校验数据和读写权限检查。

