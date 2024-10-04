```
brew bottle sold
mv sold--TAG.ARCH.bottle.1.tar.gz sold-TAG.ARCH.bottle.1.tar.gz
gh release create
-> tag version
gh release upload TAG sold-TAG.ARCH.bottle.1.tar.gz
```

