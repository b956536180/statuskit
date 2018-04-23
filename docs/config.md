# 配置「StatusKit」

## 站点配置文件

请自行根据 Hexo 官方文档进行配置。

## 主题配置文件

```yaml
head:
  favicon:
  high_res_favicon:
  keywords:
  site_verification:
    google:
    baidu:
```

- favicon: 普通 favicon
- high\_res\_favicon: 高清 favicon
- keywords: 网站关键词，将会输出在 meta keywords tag 中
- site_verification: 网站所有权验证，将会输出在页面 head 前的 meta tag 中

```yaml
appbar:
  icon:
  links:
    StatusKit:
      url: https://github.com/neoFelhz/StatusKit
    #Link2:
      #url:
```

- icon: 图标 URL，图标将会显示在顶部
- links: 显示在顶部的链接。配置文件中默认给了一个样例

```yaml
info:
  title: StatusKit
  intro:
```

- title: 显示在页面的标题
- intro: 显示在页面的 About This Site 下面的介绍

> About This Site 不可隐藏，所以强烈建议你添加页面介绍

```yaml
components:
  user_interface:
    name: User Interface
    intro: Frontend Application
    auto_expand: true
    components:
      website:
        name: Website
        intro: GitHub Repo page for StatusKit
        degree: 1
        link: https://github.com/neoFelhz
```

以 `_config.template.yml` 中自带都样例为例介绍。

- user\_interface: Component 组别的识别名，在页面中不显示，要求识别名两两不相同
- name: Component 组别的名字，显示在页面中
- intro: Component 组别的介绍，可选
- auto\_expand: 设置 Component 组别是否默认展开，设置 true/false
- components: 设置 Component 组别下属的 Component

- website: Component 的识别名，在页面中不显示。要求识别名两两不相同。
- name: Component 的标题，显示在页面中
- intro: Component 的介绍，可选
- degree: 当前 Component 的状态。1 是 Operational、2 是 Performance Issue、3 是 Partial Outage、4 是 Major Outage
- link: Component 的链接，可选。
