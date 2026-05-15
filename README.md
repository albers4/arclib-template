# arclib-template

## Rename file content
use `rg -l -i "template" | xargs sed -n 's/template/template/gip'` to check for replacements in a 'dry' run and 
use `rg -l -i "template" | xargs sed -i 's/template/template/g'` to commit to changes.

## Rename folders
mv arclib-template-spec arclib-template-spec
mv arclib-template-impl arclib-template-impl
mv arclib-template-py arclib-template-py
mv arclib-template-example arclib-template-example
mv arclib-template-py/python/arclib_template arclib-template-py/python/arclib_template
