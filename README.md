# Replace Variables

## The bash script allowing for creating templates

## The motivation 

I use tamplates in the flutter development.

Initially I wrote this in Kotlin, but I needed to use jar. Jar is closed and needs to be recompiled. I wondered if it's possible to write such a program in bash. I don't know how to write bash scripts, but with help of the internet I manage it. It wasn't a pleasant experience.

```bash

➜  replace-variables ./replace.sh -h

Example usages:

./replace.sh --argument "magnificent outcome" --type "example" --destination "../hereYouNeedToUseCorrent/Path/Names"

Options

-h --help : prints help
-v --version : prints version
-a --argument : the value that is used to replace variables in your template
-t --type : the directory of your templates
-d --destination : the destination of output
-pf --postfix-off : doesn't use template file name as a postfix

Possible variables:

_RAW_NAME_
_UPPER_CAMEL_CASE_NAME_
_CAMEL_CASE_NAME_
_SNAKE_CASE_NAME_
_DASH_CASE_NAME_

Templates have to be in "templates" directory.

```