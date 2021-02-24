# myscoop

scoop zst support:

<user folder>\scoop\current\lib\decompress.ps1 line 19 add zst
  
 ```powershell
 else {
        return $File -match '\.((gz)|(tar)|(tgz)|(lzma)|(bz)|(bz2)|(7z)|(rar)|(iso)|(xz)|(lzh)|(nupkg)|(zst))$'
    }
```
