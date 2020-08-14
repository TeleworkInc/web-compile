# web-compile

### Welcome to my [gnv project](https://github.com/TeleworkInc/gnv)!

I'm one big ES6 module, and I compile to multiple targets. 

## Installing
Clone this repository, and then enter the directory and install globally:
```bash
cd web-compile
yarn link
```

## Development

### Prerequisites
Make sure to install `gnv` globally with:
```bash
yarn global add gnv
```

### Test out the CLI
Link this package to your bin with:
```bash
yarn link
```

and then run the dev CLI (executes source at `exports/cli.js`):
```bash
web-compile-dev --help
```
```none
Usage: web-compile-dev [options] [command]

Options:
  -h, --help       display help for command

Commands:
  say-hello [msg]  Say hello, or provide a special message instead.
  help [command]   display help for command
```

Build the project with:
```bash
gnv build
```

And run the production CLI (executes release build at `dist/cli.cjs`):
```bash
web-compile --help
```

## License
I'm open source by default!

```none
Released under the MIT License

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
```