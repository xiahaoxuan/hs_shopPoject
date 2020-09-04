# hs_shopPoject
商城项目
1.创建Git仓库 添加.idea忽略文件
2.创建工程 设置manage.py 为启动文件 启动按钮旁边Edit Configurations 进入Parameters里面设置 runserver 8000
3.配置开发环境manager中改变manage.py 默认启动路径

os.environ.setdefault('DJANGO_SETTINGS_MODULE', 'meiduo_mall.settings.dev')
4. 配置jinja2模板引擎
创建templates包设置jinja2为默认模板引擎右击包Mark Derectory as Templates Folder
补充Jinja2模板引擎环境



