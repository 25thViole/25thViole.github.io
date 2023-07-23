## Blog Post Title From First Header

Due to a plugin called `jekyll-titles-from-headings` which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post. You can talk about all sorts of fun things here.

---

### This is a header

| Priority apples | Second priority |
| --- | --- |
| ambrosia | gala |
| pink lady | jazz |
| honeycrisp | granny smith |

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
>Testing is good

> Testing again
> and again
> > and again.

Testing colors a bit `#12e876`. Wow!

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:



```powershell
PS C:\Users\George> ls


    Directory: C:\Users\George


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          8/4/2020  12:20 PM                .cache
d-----         4/14/2021   3:03 PM                .config
d-----         6/24/2022   7:48 AM                .ms-ad



PS C:\Users\George> cd ./cache
cd : Cannot find path 'C:\Users\George\cache' because it does not exist.
At line:1 char:1
+ cd ./cache
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Users\George\cache:String) [Set-Location], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand

PS C:\Users\George> cd ./.cache
PS C:\Users\George\.cache>

```

