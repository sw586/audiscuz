# audiscuz
这个Python脚本是一个自动登录hostloc.com   Discuz!论坛

程序主要分为以下几个部分：

随机生成用户空间链接：randomly_gen_uspace_url函数生成一个包含随机用户ID的URL列表。
登录账户：login函数使用给定的用户名和密码登录论坛。
检查登录状态：check_login_status函数检查是否成功登录。
打印当前积分：print_current_points函数打印当前账户的积分。
获取积分：get_points函数访问随机生成的用户空间链接来获取积分。
打印当前IP地址：print_my_ip函数打印当前使用的IP地址。
主函数：在__name__ == "__main__"块中，程序从环境变量中读取用户名和密码，然后依次登录每个账户并获取积分。
访问https://hostloc.com/forum.php?mod=viewthread&tid=1218747&page=1#pid14626992并且回复：“自己顶”
