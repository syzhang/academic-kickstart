## reminder for how to update
### get the theme after clone
```
git submodule update --init --recursive
```
### remove existing public dir (manual)
```
rm -r public/
```
### reactivate public
```
git submodule add -f -b master https://github.com/syzhang/syzhang.github.io.git public
```
### update contents and build
```
.\hugo.exe
.\hugo.exe server
```
### rebuild public
```
hugo
cd public
git add .
git commit -m "Build website"
git push origin master
cd ..
```