
## Installation

```
### Required packages
# pip3 install -U requests scrapy tqdm prettytable numpy matplotlib

pip3 install bocfx
```

## Basic Usage
###### As stand-alone	 application

```
>> bocfx
```

###### As module

```
from bocfx import bocfx

bocfx()
```

## Advanced Usage
###### As stand-alone	 application

```
bocfx -f -s -t -p -c -o
```

###### As module

```
from bocfx import bocfx

bocfx(FX=0, sort=0, time=-1, plot=0, csv=0, pt=0, op='~/bocfx')
```

## MIT Licence

Copyright (c) 2018 The Python Packaging Authority

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

