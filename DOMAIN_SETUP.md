# 自定义域名设置说明

## 如果你想使用自定义域名（如 peishiliu.com），请按以下步骤操作：

### 1. 购买域名
- 推荐域名注册商：Namecheap, Google Domains, GoDaddy
- 建议域名：peishiliu.com, peishi-liu.com, 或类似的

### 2. 配置 CNAME 文件
将你购买的域名写入 CNAME 文件中，例如：
```
peishiliu.com
```

### 3. 配置 DNS 设置
在你的域名注册商处设置 DNS 记录：
- 类型：CNAME
- 主机：www（或 @）
- 值：from1tomax.github.io

### 4. 更新 _config.yml
将 _config.yml 中的 url 改为你的自定义域名：
```yaml
url: "https://peishiliu.com"
```

### 5. 等待生效
DNS 设置通常需要几小时到48小时生效。

## 当前配置
目前网站使用默认的 GitHub Pages 域名：https://from1tomax.github.io
