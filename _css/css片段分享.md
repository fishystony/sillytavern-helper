---
title: css片段分享
date: 2025-03-26
layout: post
---

> 所有片段都是无偿公开分享（反正也是靠G大师搓的，大家随便用嘻嘻）
> 
> 需要改色改内容的可以直接扔给G大师或者美化大师，说一下要求就行了

## Warning警示栏
使用方式：大概是角色卡介绍页

```
<div style="
  background: linear-gradient(135deg, rgba(230, 230, 250, 0.9), rgba(221, 160, 221, 0.9));
  border: 2px solid #DDA0DD;
  border-radius: 8px;
  padding: 15px 10px;
  text-align: center;
  color: #483D8B;
  font-size: 16px;
  position: relative;
  box-shadow: 0 0 10px rgba(221, 160, 221, 0.6), 0 0 20px rgba(216, 191, 216, 0.4);
  max-width: calc(100% - 40px);
  margin: 20px auto;
  word-wrap: break-word;
  overflow-wrap: break-word;
  backdrop-filter: blur(6px);
">
  <span style="
    display: inline-block;
    font-size: 20px;
    color: #483D8B;
    margin-bottom: 8px;
    text-shadow: 0 0 6px #DDA0DD, 0 0 12px #E6E6FA;
  ">
    𝑾𝒂𝒓𝒏𝒊𝒏𝒈：
  </span><br>
  <span style="
    line-height: 1.4;
    font-style: italic;
    color: #483D8B;
    text-shadow: 0 0 4px #DDA0DD, 0 0 8px rgba(230, 230, 250, 0.8);
  ">
    此卡仅限内部交流使用，严禁外传、私自二改与盗用！！
  </span>
</div>
```
![image](https://raw.githubusercontent.com/fishystony/sillytavern-helper/main/image/2025-03-26%2017.58.28%20localhost%205eddeb2dad35.png)
