```
rm -rf image1
rm -rf image2
git clone https://github.com/vimerzhao/images image1
git clone https://github.com/vimerzhao/images image2

cd image1
rm -rf *
git add . && git commit -m "clean"
git push
cd ..
cd image2
rm -rf .git

// 修改处理
git init
git add .
git commit -m "reset again"
git remote add origin https://github.com/vimerzhao/images.git
git push origin master --force
```

[https://batchwatermark.com](https://batchwatermark.com)
