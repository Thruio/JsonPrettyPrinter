# JsonPrettyPrinter

### Install

1. Use [Composer](http://getcomposer.org) to install JsonPrettyPrinter into your project:

    ```bash
    composer require thru.io/json-pretty-printer
    ```

2. Use it as follows:

    ```bash
    use \Thru\JsonPrettyPrinter\JsonPrettyPrinter;

    $json = JsonPrettyPrinter::Json($object);
    ```