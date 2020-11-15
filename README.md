# sanic_brotli
Brotli Compression Algorithm on Sanic responses.

## Installation
`pip install sanic-brotli-linkin`

## Usage
```python
from sanic import Sanic
from sanic_brotli import Compress

app = Sanic(__name__)
Compress(app)

```
