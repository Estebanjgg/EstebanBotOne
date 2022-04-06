# Starting to create bot integration with python.

## install first  library

pip install slackclient

[pip python-dotenv](https://pypi.org/project/python-dotenv/)

First part of the code

The code show gives us a simple message of hello world

import slack
import os
from pathlib import Path
from dotenv import load_dotenv

env_path = Path('.') / '.env'
load_dotenv(dotenv_path=env_path)

client = slack.WebClient(token=os.environ["SLACK_TOKEN"])

client.chat_postMessage(channel='#test1', text='que onda')


![](image/README/1649133010761.png)

**create a file extension .py**

**create a file extencion .env**

![](image/README/1649133119449.png)

### Import , Install extencion for the Marketplace

![](image/README/1649133241518.png)


# Two part of the code

pip install flask

pip install slackeventsapi

pip install Jinja2
pip install MarkupSafe
pip install MarkupSafe

https://ngrok.com/download


[ngrok-stable-windows-amd64.zip](https://github.com/Estebanjgg/EstebanBotOne/files/8423536/ngrok-stable-windows-amd64.zip)
