# JsonPrettyPrinter

[![Build Status](https://travis-ci.org/Thruio/JsonPrettyPrinter.svg?branch=master)](https://travis-ci.org/Thruio/JsonPrettyPrinter) [![Code Climate](https://codeclimate.com/github/Thruio/JsonPrettyPrinter/badges/gpa.svg)](https://codeclimate.com/github/Thruio/JsonPrettyPrinter) [![Test Coverage](https://codeclimate.com/github/Thruio/JsonPrettyPrinter/badges/coverage.svg)](https://codeclimate.com/github/Thruio/JsonPrettyPrinter)

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