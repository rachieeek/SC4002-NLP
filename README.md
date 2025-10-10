# SC4002 Natural Language Processing

Repository for Nanyang Technological University SC4002 Natural Language Processing Group Project.

## Group Members

- Koh Jia Hui Rachel
- Celeste Ang Jianing
- Lim Kiat Sen, Jaron
- Asher Lim Guojun
- Pang Boslyn

## Setup

ensure you have uv pip installed. In project directory,

1. uv sync
2. source .venv/bin/activate
3. select the .venv as a kernel

Package tracking:

uv add: torchtext==0.4.0 as per assignment instructions.
uv add: spacy>=3.7.2,<3.8.0
uv add: https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.7.1/en_core_web_sm-3.7.1.tar.gz as uv doesn't use pip
