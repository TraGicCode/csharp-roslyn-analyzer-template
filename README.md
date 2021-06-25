# Installing modulesync


## windows

```
choco install ruby -y
choco install msys2 -y
Update-SessionEnvironment
ridk install 2 3
gem install modulesync
msync --help
```

## docker
```
> docker run --rm -it -v C:\source\tragiccode\csharp-roslyn-analyzer-template:/csharp-roslyn-analyzer-template -w /csharp-roslyn-analyzer-template ruby sh
> gem install modulesync
> msync --help
```

# Installing rubocop

rubop cop helps make sure the ruby code in your templates are linted.

```
> gem install rubocop
> rubocop -a
```

# Usecases

https://github.com/TraGicCode/modulesync_configs