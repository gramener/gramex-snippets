# gramexsnippets README

`YAML` code snippets for `Gramex` endpoints.

## Requirements

Needs `VSCode 1.31` or above.

## How to use

In `gramex.yaml` or any `.yaml` file, type `grx-form`... it should prompt two `FormHandler` related snippets as suggestions.

Supported snippet commands:

- `grx-filehandler`
- `grx-functionhandler`
- `grx-formhandler-db`
- `grx-formhandler-csv`
- `grx-email`
- `grx-custom-session`
- `grx-custom-log`
- `grx-cache-assets`
- `grx-auth-db`
- `grx-auth-google`
- `grx-auth-simple`
- `grx-alert`
- `grx-capture`
- `grx-schedule`

![how gramex snippet works](images/gramex-snippets.gif)

Use `tab` to change default parameters.

## Features

Auto-complete YAML configuration for `Gramex` endpoints.

Current features:

- Handlers
  - `FileHandler` endpoint
  - `FormHandler` flat files and database endpoints
  - `FunctionHandler`
- `auth` endpoints (`DBAuth`, `GoogleAuth`, `SimpleAuth`)
- Custom `log` and `session` configurations
- Services: `email`, `alert`, `capture`, `schedule`
- Caching assets

## Release Notes

Current features include configuration for `FormHandler`, `log`, `session`, `email`, caching assets

View `CHANGELOG` for release-wise changes.
