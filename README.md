# Office Converter
#### PHP Wrapper for LibreOffice

Convert offices files to PDF and HTML using LibreOffice or OpenOffice.
Supported conversion formats include:

* pptx => pdf,
* ppt => pdf
* pdf => pdf
* docx => pdf, odt, html
* doc => pdf, odt, html
* wps => pdf, odt, html
* dotx => pdf, odt, html
* docm => pdf, odt, html
* dotm => pdf, odt, html
* dot => pdf, odt, html
* odt => pdf, html
* xlsx => pdf
* xls => pdf
* csv => pdf
* png => pdf
* jpg => pdf
* jpeg => pdf
* jfif => pdf
* PPTX => pdf
* PPT => pdf
* PDF => pdf
* DOCX => pdf, odt, html
* DOC => pdf, odt, html
* WPS => pdf, odt, html
* DOTX => pdf, odt, html
* DOCM => pdf, odt, html
* DOTM => pdf, odt, html
* DOT => pdf, odt, html
* ODT => pdf, html
* XLSX => pdf
* XLS => pdf
* PNG => pdf
* JPG => pdf
* JPEG => pdf
* JFIF => pdf
* Pptx => pdf
* Ppt => pdf
* Pdf => pdf
* Docx => pdf, odt, html
* Doc => pdf, odt, html
* Wps => pdf, odt, html
* Dotx => pdf, odt, html
* Docm => pdf, odt, html
* Dotm => pdf, odt, html
* Dot => pdf, odt, html
* Ddt => pdf, html
* Xlsx => pdf
* Xls => pdf
* Png => pdf
* Jpg => pdf
* Jpeg => pdf
* Jfif => pdf
* rtf  => docx, txt, pdf
* txt  => pdf, odt, doc, docx, html

### Installation

It is recommended to install OfficeConverter through [Composer](http://getcomposer.org/).

Run this command within your project directory

```shell
composer require ncjoes/office-converter
```

### Dependencies
In order to use OfficeConverter, you need to install [LibreOffice](http://www.libreoffice.org/).

### Usage

Here are some samples.

```php
<?php
// if you are using composer, just use this
use NcJoes\OfficeConverter\OfficeConverter;

$converter = new OfficeConverter('test-file.docx');
$converter->convertTo('output-file.pdf'); //generates pdf file in same directory as test-file.docx
$converter->convertTo('output-file.html'); //generates html file in same directory as test-file.docx

//to specify output directory, specify it as the second argument to the constructor
$converter = new OfficeConverter('test-file.docx', 'path-to-outdir');
?>
```

### License
The OfficeConverter package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

### Feedback & Contribute

Notify me of any issues, bugs, or improvements. Thanks :+1:
