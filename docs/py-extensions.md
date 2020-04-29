# PyMdown Extensions tests

## Arithmatex

$$
E(\mathbf{v}, \mathbf{h}) = -\sum_{i,j}w_{ij}v_i h_j - \sum_i b_i v_i - \sum_j c_j h_j
$$

\[3 < 4\]

\begin{align}
    p(v_i=1|\mathbf{h}) & = \sigma\left(\sum_j w_{ij}h_j + b_i\right) \\
    p(h_j=1|\mathbf{v}) & = \sigma\left(\sum_i w_{ij}v_i + c_j\right)
\end{align}

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
