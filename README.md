## regular-show
> Get your favorite name in Regular Show

This name lists are just JSON files and you can use wherever.

## Usage
```shell
var regularShow = require('regular-show');

regularShow();
//=> Mordecai

regularShow();
//=> Rigby

regularShow.words;
// ['Mordecai', 'Rigby', ...]
```

## API
regularShow()

Type: `string`

Random charcater's name in Regular Show.

regularShow.names

Type: `array`

Fetch all of the names.

## CLI
```shell
$ npm i regular-show -g
```

```shell
$ npm regular-show --help
  
  Get your favorite name in Regular Show

  Examples
    $ regular-show
    Mordecai

    $ regular-show --all
    Rigby
    Eileen
    Muscle Man
    ...

  Options
    --all  Fetch all the names rather than a random name
```

## License
MIT © [WeiChiaChang](https://github.com/WeiChiaChang)