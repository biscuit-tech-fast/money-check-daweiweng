# 资产配置自查 · 大卫翁方法论

一个单文件的个人财务自查工具：**填入你的数字 → 直接告诉你现在处在哪个阶段、今天该做什么。**

- 纯静态、零依赖、离线可用（数据只存在访问者本机浏览器，不上传）
- 手机上自动适配单列排版；结果可复制为 Markdown 或打印成 PDF
- 规则依据：大卫翁《资产配置行动指南》（中信出版社 2026）+ 播客《嗨咻》110 期
- 页面上标 `[书·N章]` 的为原书规则，标 `[推演]` 的为把书中框架套到「创业者 / 无存款 / 收入不稳定」处境上的推论

## 判断逻辑

```
关键数字缺失                  → 阶段 0  建立财务地图
有高息负债 / 个人担保 / 社保断缴  → 阶段 1  止血与隔离
现金类 C ÷ M < 3 个月          → 阶段 2  建安全垫（L1 / L2）
现金类 C ÷ M ≥ 3 个月          → 阶段 5  启动三笔钱（3–6 / 6–12 / ≥12 三档）
```

安全垫只算现金 + 货基 + 定存（书中：第一笔钱「不要想着去投资、理财、买股票、买基金」）；
消费阈值公式则用全部流动资产 —— 两个口径在书里本来就不同，所以分开计算。

## 本地使用

浏览器直接打开 `index.html`

## 部署（GitHub Pages）

```bash
git remote add origin https://github.com/biscuit-tech-fast/money-check.git
git push -u origin main
```

然后仓库 → Settings → Pages → Source 选 `Deploy from a branch`，Branch 选 `main` / `(root)`，Save。
访问 `https://biscuit-tech-fast.github.io/money-check/`

> 免费版 GitHub Pages 需要仓库为 public。`.nojekyll` 别删。

---

本工具是个人财务管理自查，**不构成投资、法律或税务意见**。
