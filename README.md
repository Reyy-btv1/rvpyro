<p align="center">
    <a href="https://github.com/Reyy-btv1/rvpyro">
        <img src="logo.png" alt="rvpyro" width="128">
    </a>
    <br>
    <b>Telegram MTProto API Framework for Python</b>
    <br>
    <a href="https://github.com/Reyy-btv1">
        Homepage
    </a>
    •
    <a href="https://github.com/Reyy-btv1/rvpyro">
        Documentation
    </a>
    •
    <a href="https://github.com/Reyy-btv1/rvpyro/issues">
        Issues
    </a>
    •
    <a href="https://t.me/reyysupport">
        Support Chat
    </a>
    •
    <a href="https://t.me/reyybackup1">
        News/Releases
    </a>
</p>

## rvpyro

> Elegant, modern and asynchronous Telegram MTProto API framework in Python for users and bots

``` python
from pyrogram import Client, filters

app = Client("my_account")


@app.on_message(filters.private)
async def hello(client, message):
    await message.reply("Hello from rvpyro!")


app.run()
```

**rvpyro** is a modern, elegant and asynchronous [MTProto API](https://pyrofork.mayuri.my.id/main/topics/mtproto-vs-botapi)
framework. It enables you to easily interact with the main Telegram API through a user account (custom client) or a bot
identity (bot API alternative) using Python.

### Support

If you'd like to support, you can consider:

- [Become a GitHub sponsor](https://github.com/sponsors/Reyy-btv1).

### Key Features

- **Ready**: Install rvpyro with pip and start building your applications right away.
- **Easy**: Makes the Telegram API simple and intuitive, while still allowing advanced usages.
- **Elegant**: Low-level details are abstracted and re-presented in a more convenient way.
- **Fast**: Boosted up by [TgCrypto](https://github.com/pyrogram/tgcrypto), a high-performance cryptography library written in C.  
- **Type-hinted**: Types and methods are all type-hinted, enabling excellent editor support.
- **Async**: Fully asynchronous (also usable synchronously if wanted, for convenience).
- **Powerful**: Full access to Telegram's API to execute any official client action and more.

### Installing

``` bash
pip3 install git+https://github.com/Reyy-btv1/rvpyro.git
```

### Resources

- Check out the source code at https://github.com/Reyy-btv1/rvpyro to learn more about rvpyro, get started right away and discover more in-depth material for building your client applications.
- Join the support chat at https://t.me/reyysupport and channel at https://t.me/reyybackup1 to stay tuned for news, updates and announcements.
