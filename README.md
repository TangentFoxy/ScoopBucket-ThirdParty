# ScoopBucket-ThirdParty
Bucket for Scoop to install cool stuff I didn't make. (http://scoop.sh)

## Usage

1. Install [Scoop](http://scoop.sh/).
```powershell
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

2. Add the bucket!
```
scoop bucket add g3-bucket https://github.com/Guard13007/ScoopBucket-ThirdParty
```

3. Install all the things!
```
scoop install love
```
