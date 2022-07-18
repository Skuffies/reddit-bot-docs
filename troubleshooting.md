# Troubleshooting

In this page we will outline some common errors that you may encounter in the process of installing and running the bot.

## Error 1: 400 Eror

This error means that your credentials are not set wright.

Check your credentials. If this error continues, try to add the name of the bot to developers. If that does not work, and you have a password less login (eg, google or apple), remove it and ad a password.

## Error 2: x: command not found

It probably means you did not install something, or that the command you typed is wrong.

## Error 3: can't open file 'main.py': [Errno 2] No such file or director no such file or directory

This means you are not the wright folder. Make shore you are in the correct folder.

## Error 4: package not found

You did not install the pip packages

Install them by running

```shell
pip install -r requirements.txt
```

Or

```shell
pip3 install -r requirements.txt
```

If you have a problem with a specific package, (eg: rich) install them by themselves.

```shell
pip3 install rich
```

If you have any other problems, checkout the [github repository](https://github.com/elebumm/RedditVideoMakerBot)
