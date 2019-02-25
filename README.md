# TelegramNameUpdating

Update (first/last/user) name of Telegram user every 30 seconds. 

参考文档：[Telethon](https://telethon.readthedocs.io/en/stable/)

基于：<https://github.com/xyou365/Telegram-Name-Updating>

## 0. 准备

运行环境：VPS，python3，python3-pip

创建应用：<a href="https://my.telegram.org/">https://my.telegram.org/</a>。只要填App title和Short name即可。获得api_id和api_hash。

## 1. 下载Demo小程序到VPS上

``` bash
git clone https://github.com/MoonBegonia/TelegramNameUpdating.git
cd TelegramNameUpdating
```

## 2. 安装telethon

``` bash
pip3 install -r requirements.txt
```

## 3. 运行Demo小程序

``` bash
python3 tg_username_update.py
```

## 4. api认证和用户登陆

根据提示输入api_id 和 api_hash。接着输入手机号和验证码，如果账号开启了二次验，则根据提示再输入二次验证的密码。最后看到 It works! 表明成功了。 默认的是每30秒钟按照一定概率更新一次lastname 到特定模式。