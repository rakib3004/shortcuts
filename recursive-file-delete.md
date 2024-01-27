# Delete all files in recursive folders
```bash
forfiles /S /C "cmd /c if @isdir==FALSE del @path"
```
