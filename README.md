> Do not use this until it's absolutely necessary! This repo has only minor fixes.

# PHPExcel - DEAD (fixes for PHP > 8 version)

PHPExcel last version, 1.8.1, was released in 2015. The project was officially deprecated in 2017 and permanently archived in 2019.

The project has not be maintained for years and must not be used anymore. **All users must migrate** to its direct successor [PhpSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet), or another alternative.

## License

PHPExcel is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE)](https://github.com/PHPOffice/PHPExcel/blob/master/license.md)

## Usage in composer

```
{
  "minimum-stability": "dev",
  "prefer-stable": true,
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/fedek6/PHPExcel"
    }
  ],
  "require": {
    "phpoffice/phpexcel": "dev-main"
  }
}
```
