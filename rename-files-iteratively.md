```bash
$count = 1; Get-ChildItem | ForEach-Object {Rename-Item $_ -NewName ("image_" + $count + $_.Extension); $count++}
```
