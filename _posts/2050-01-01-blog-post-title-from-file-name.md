## Blog Post Title From First Header

Thanks to a plugin called `jekyll-titles-from-headings`, supported by GitHub Pages by default, the above header (in the markdown file) will be automatically used as the page title.

If the file does not start with a header, then the post title will be derived from the filename.

---

### This is a header

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
