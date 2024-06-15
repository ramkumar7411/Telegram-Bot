<p align="center">
<img src="docs/images/Chatting%20with%20Python.png" alt="thumbnail" width=600px>
</p>
<h1 align="center"> run-py-bot </h1>

<p align="center">
Run python code from your telegram chat!
</p>
<!-- A simple bot that runs python code. Free and Open Source. For more info visit http://bit.ly/runPython -->

> **UPDATE** I am no longer running this bot on my server. Please deploy your own instance to use.


## Featured in 😍

1. Tweet by [Dev Community](https://twitter.com/ThePracticalDev/status/1325386583537803264)
2. Tweet by [The Python Dev](https://twitter.com/The_Python_DEV/status/1325237102058016768)
3. Dor Moshe's [Newsletter](https://dormoshe.io/newsletters/ag/python/7?utm_source=twitter&utm_campaign=twitter)
4. My YouTube Video [Chatting with Python](https://youtu.be/nCuQ-7Rw0gM)

## Example Use 🔀

You may use pythonic expressions to easily calculate any complex problem. Or you may test your algorithms on the go.

<p align="center">
<img src="docs/images/run_python_bot_v0.1+.gif" alt="demo" >
</p>

## How to run 🤖

You can easily run your own instance of the bot.

You can run on any OS (windows/mac/linux). For better reliability, you may deploy to a VPS like Digital Ocean Droplet. You can even run on Android, using the Termux app.

Open your terminal and follow the instructions to run the bot.

> **Note:** Use python 3.8

- Make sure you have `git`, `python` and `pip`.

    ```bash
    # the following commands should not produce error
    git --version
    python --version # 3.8 is recommended
    pip --version
    ```

    > **Note:** In some systems `python` version 3 is availaible as `python3`

- First of all, clone the repository and move into the `run-py-bot` directory.

    ```shell
    git clone https://github.com/aahnik/run-py-bot.git && cd run-py-bot
    ```

- Create a python virtual enviroment and activate it.

    ```bash
    python -m venv .venv # create
    source .venv/bin/activate # activate (unix)
    # the command to activate virtual environment is different for Windows, google search
    ```

- Install the requirements.

    ```bash
    pip install -r requirements.txt
    ```

- Set `API_TOKEN` environment variable. Write the following into a file named `.env`.

    ```bash
    API_TOKEN=1234fsjksjfls23r4
    # use your own real token
    ```

    You can create a new bot and get token from [@BotFather](https://telegram.me/BotFather).

- Run the `start.py`, and you are good to go.

    ```shell
    python start.py
    ```

