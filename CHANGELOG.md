# Changelog portable-vscode-updater 

## 2.0.0 - 2022-06-04

- allow self upgrading via `codeup upgrade-self` (uses package `modup` for this)

## 2.0.0-beta.4 - 2022-06-01
- change temp file generation to put the update zip at the end (suffixing the random portion) to avoid problems with zip unpack

## 2.0.0-beta.3 - 2022-06-01
- improve readme general package information and "How to use" section
- deploy to second deno module: https://deno.land/x/portable_vscode_manager

## 2.0.0-beta.2 - 2022-06-01
- regenerate description on deno.land/x

## 2.0.0-beta.1 - 2022-06-01

- complete rewrite, has a correct cli interface now with more options 
  (is not complete yet, though)
- can now be installed via `deno install` (see Readme)

## 1.1.0 

- add a way to force extraction of files from update-zip even when some files are already available
- add better version reporting

## 1.0.0 

- initial release 
- IMPORTANT: This script assumes to be started inside an extracted vscode installation