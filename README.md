To run, just use command:

```docker run -d --name=telegram_proxy -p 1080:1080 --restart=always koppektop/telegram-proxy```

To build:

```
git clone https://github.com/akolnoochenko/telegram_proxy.git/
cd telegram_proxy/
git submodule init
git pull --recurse-submodules && git submodule update --recursive
docker build -t koppektop/telegram-proxy .
```
