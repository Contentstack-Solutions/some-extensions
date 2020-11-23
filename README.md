# some-extensions
Some Extensions from Oskar

## image-preview
A preview of the image in the entry - Just a bigger view. Using the image delivery API.

Config Parameter Example:
```
{
    "imageField": "image",
    "region": "https://eu-images.contentstack.com"
}
```
`imageField` is just the uid of the image field that the preview will be created from.
`region` can be https://eu-images.contentstack.com or https://images.contentstack.io

## summernote-rte
https://summernote.org/ - Custom field RTE

## value-in-master-locale
Shows the value of some entry in the master language. Nice to have in localized versions of entries if you quickly want to see a field value from the master language.

Config Parameter Example:
```
{
    "field_uid": "textfield",
    "master_locale": "en-us"
}
```
`field_uid` is the field you want to show the value from.
