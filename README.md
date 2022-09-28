# Cabeceras

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# Underlines
Underline 1
----------

Underline 2
======

# Enfasis
- *italica*
- _italica_
- **bold** o __strong__
- ~~tachado~~

# Listas
1. lista ordenada
1. lista ordenada
1. lista ordenada

- lista
- lista
- lista


# links
- <a href="www.google.com">link html</a>
- [link markdown](www.google.com)

# images
![logo grithub](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

# code snipets

```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
```PHP
require_once 'Zend/Uri/Http.php';

namespace Location\Web;

interface Factory
{
    static function _factory();
}

abstract class URI extends BaseURI implements Factory
{
    abstract function test();

    public static $st1 = 1;
    const ME = "Yo";
    var $list = NULL;
    private $var;

    /**
     * Returns a URI
     *
     * @return URI
     */
    static public function _factory($stats = array(), $uri = 'http')
    {
        echo __METHOD__;
        $uri = explode(':', $uri, 0b10);
        $schemeSpecific = isset($uri[1]) ? $uri[1] : '';
        $desc = 'Multi
line description';

        // Security check
        if (!ctype_alnum($scheme)) {
            throw new Zend_Uri_Exception('Illegal scheme');
        }

        $this->var = 0 - self::$st;
        $this->list = list(Array("1"=> 2, 2=>self::ME, 3 => \Location\Web\URI::class));

        return [
            'uri'   => $uri,
            'value' => null,
        ];
    }
}

match ($key) {
    1 => 'Integer 1',
    '1' => 'String 1',
    true => 'Bool true',
    [] => 'Empty array',
    [1] => 'Array [1]',
};

enum Foo: string {
    case Test = 'test';
}

echo URI::ME . URI::$st1;

__halt_compiler () ; datahere
datahere
datahere */
datahere
```

