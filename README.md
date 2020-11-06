## product association website

### Setup
```
npm install -g harp
```

### Development
```
harp server src
```

Go to localhost:9000

### Deployment
```bash
harp compile src docs
git add .
git commit -m "Recompiled."
git push origin master
```
