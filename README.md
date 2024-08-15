# uuid-cli

Just a quick utility to generate uuid's from the command-line using existing go libraries.

## example

And a quick shell function to generate an id and copy it to the clipboard
```shell
uuid() {
  UUID=$(uuid-cli)
  echo "$UUID has been copied to the clipboard"
  echo "$UUID" | pbcopy
}
```