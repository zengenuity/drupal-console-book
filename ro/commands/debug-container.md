# debug:container
Afișează serviciile curente pentru o aplicație.

**Usage:**
```
drupal debug:container [arguments] [options]
dco
```

## Available options
Option | Details
-------|-------------
--parameters | Service name.

## Available arguments
Argument | Details
---------|-------------
service | Service name.
method | Method name.
arguments | Array of Arguments in CSV or JSON format.

## Examples
* Displays the views.views_data_helper services
```
drupal debug:container views.views_data_helper
```
