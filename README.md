# hexo-pupa-theme

个人使用的博客主题

![pupa-theme](./screen.png)

## 安装

```bash
npm install
```

各种依赖参考[pupa](https://github.com/xwartz/pupa)

## 启用

修改 `_config.yml` 的 `theme` 配置项为 `pupa`:

```yaml
theme: pupa

# 在归档页面显示所有文章
archive_generator:
  per_page: 0
  yearly: false
  monthly: false
  daily: false
```

## 更新

``` bash
cd themes/pupa
git pull
```

## License

MIT
