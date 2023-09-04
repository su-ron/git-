

[Git（分布式版本控制工具）_塞班呢的博客-CSDN博客](https://blog.csdn.net/a18307096730/article/details/124586216?spm=1001.2014.3001.5502)

[07_git常用指令_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1MU4y1Y7h5?p=7&spm_id_from=pageDriver&vd_source=e6a100138906f3892c6413488ca8e688)



使用说明

**or create a new repository on the command line**

```
echo "# detail-of-stm32-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:su-ron/detail-of-stm32-project.git
git push -u origin main

git add .
git commit -m 'commit 001'
git push origin main
```

**or push an existing repository from the command line**

```
git remote add origin git@github.com:su-ron/detail-of-stm32-project.git
git branch -M main
git push -u origin main
```

