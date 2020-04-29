# PyMdown Extensions tests

## Arithmatex

$p(x|y) = \frac{p(y|x)p(x)}{p(y)}$, \(p(x|y) = \frac{p(y|x)p(x)}{p(y)}\).

## Caret

^^Insert me^^

## Details

??? success
   Content.

??? warning classes
   Content.

## Emoji

:smile: :heart: :thumbsup:

## Extra

???

## Highlight

```php
<?php

namespace Library\Carrier\DHL\Integration\Client;

use Library\AbstractClient;
use Library\Carrier\DHL\Integration\Configuration\DHLPaketConfiguration;

class DHLPaketLocationGermanyClient extends AbstractClient
{
    const BASE_SOAP_TEST_URI = 'https://cig.dhl.de/services/sandbox/soap';
    const BASE_SOAP_PROD_URI = 'https://cig.dhl.de/services/production/soap';
    const BASE_WSDL_URL      = __DIR__ . '/../../Integration/Library/DHLPaketLocationGermany/Schema/dhlpacket-germany-standortsuche-api-1.1.wsdl';
}
```

## InlineHilite

Here is some code: `#!py3 import pymdownx; pymdownx.__version__`.

The mock shebang will be treated like text here: ` #!js var test = 0; `.

## Keys

++ctrl+alt+delete++

## MagicLink

- Just paste links directly in the document like this: https://google.com.
- Or even an email address: fake.email@email.com.

## Mark

==mark me==

==smart==mark==

## ProgressBar

[=85% "85%"]{: .candystripe}

## SmartSymbols

(tm) (c) (r) <--> +/- 1/4, etc. 1st 2nd etc.

## SuperFences

Paragraph.

```
a fenced block
```

Another paragraph.

## Tabbed

=== "Tab 1"
    Markdown **content**.

    Multiple paragraphs.

=== "Tab 2"
    More Markdown **content**.

    - list item a
    - list item b

## Tasklist

- [X] item 1
    * [X] item A
    * [ ] item B
        more text
        + [x] item a
        + [ ] item b
        + [x] item c
    * [X] item C
- [ ] item 2
- [ ] item 3

## Tilde

~~Delete me~~
