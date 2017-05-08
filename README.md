HttpError
===============
2017-04-06



Widget for displaying an HttpError.




This is a widget for the [kamille framework](https://github.com/lingtalfi/Kamille).


Install
===========
using the [kamille installer tool](https://github.com/lingtalfi/kamille-installer-tool)
```bash
kamille winstall HttpError
```



Model
===========

This model contains the following variables:

- code: the http code (like 404, 403, etc...)
- text: a text explaining the code



Demo snippet
=========

```php
<?php


$conf = [
    "layout" => [
        "tpl" => "splash/default",
    ],
    "widgets" => [
        "main.httpError" => [
            "tpl" => "HttpError/default",
            "conf" => [
                "code" => 404,
                "text" => "Page not found",
            ],
        ],
    ],
];
```






History Log
------------------
    
- 1.1.2 -- 2017-04-07

    - fix theme files

- 1.1.1 -- 2017-04-07

    - fix template

- 1.1.0 -- 2017-04-07

    - add css file

- 1.0.1 -- 2017-04-06

    - fix forgot HttpErrorWidgetInstaller

- 1.0.0 -- 2017-04-06

    - initial commit