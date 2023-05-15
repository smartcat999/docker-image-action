# Hello world docker action

This action check image security options to greet to the log.

## Inputs

## `image-check`

**Required** Security options for image to be checked. Default `"tools"`.

## `image`

**Required** Image to be checked.

## `output`

**Required** Image check result. Default `"result.txt"`.

## Outputs

## `result`

Image check result.

## Example usage

uses: actions/docker-image-action@v2
with:
image-check: tools
image: node:latest
output: tools.txt