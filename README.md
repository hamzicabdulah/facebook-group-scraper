## Synopsis

Command line program that downloads all the files or photos of a Facebook group. Still in development, and currently works only for downloading group files (**doesn't work for images**), and it only works for groups with a small number of files.

## Command Usage Format

`node download <type> <FB email> <FB password> <FB group url>`

Type can only be "photos" (currently not available) or "files"

## Usage Example

To download all group files:
`node download files my_facebook_email@email.com my_password https://www.facebook.com/groups/359999434098189`

To download all group photos:
`node download photos my_facebook_email@email.com my_password https://www.facebook.com/groups/359999434098189`

## Installation

To install all package dependencies:
`npm install`

Please install the appropriate chilkat package for your system manually, by running:
`npm install <chilkat package name>`

You can see the available Chilkat packages [here](https://www.npmjs.com/~chilkat). 