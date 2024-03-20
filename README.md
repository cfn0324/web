# 安装MkDocs
```
pip install mkdocs
```
# clone此库
```
git clone https://github.com/ctguacm/ctguacm.github.io.git
```
# 部署网站
```
mkdocs build
mkdocs gh-deploy
git add .
git commit -m "web"
git push origin main
```