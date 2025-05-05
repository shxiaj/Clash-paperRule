# Clash-paperRule
Clash文献出版社直接代理规则

在校使用校园网浏览下载文献时，跳过这些出版社的网站代理
使用方式: Clash中点击配置那块, 选中一个配置编辑, 将规则添加至最后, 看配置文件具体情况缩进和添加单引号 
```yaml
- DOMAIN-SUFFIX,manual.gromacs.org,DIRECT
- DOMAIN-KEYWORD,sci-hub,DIRECT
- DOMAIN-SUFFIX,ccdc.cam.ac.uk,DIRECT
- DOMAIN-KEYWORD,wiley,DIRECT
- DOMAIN-KEYWORD,pubs,DIRECT
- DOMAIN-KEYWORD,translate,DIRECT
- DOMAIN-KEYWORD,docs,DIRECT
- DOMAIN-KEYWORD,onenote,DIRECT
- DOMAIN-KEYWORD,office,DIRECT
- DOMAIN-KEYWORD,microsoft,DIRECT
- DOMAIN-SUFFIX,digicert.com,DIRECT
- DOMAIN-SUFFIX,sciencedirect.com,DIRECT
- DOMAIN-SUFFIX,iresearchbook.cn,DIRECT
- DOMAIN-SUFFIX,elsevier.com,DIRECT
- DOMAIN-SUFFIX,nature.com,DIRECT
- DOMAIN-SUFFIX,webofknowledge.com,DIRECT
- DOMAIN-SUFFIX,pubs.acs.org,DIRECT
- DOMAIN-SUFFIX,scitation.org,DIRECT
```

如果需要配置更新时自动添加, 设置->配置预处理 功能中设置, 具体可Google
