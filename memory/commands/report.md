# /report <ticker> [--lang zh|en]

生成一份专业的股票研报 PDF。

## 触发方式
- `/report PDD`
- `/report AAPL --lang en`
- `帮我生成 PDD 的研报`
- `/report 中远海控 中文`

## 参数
- `ticker`（必填）：股票代码或中文名
- `--lang`（可选）：zh（默认）或 en。"中文"/"英文" 等自然语言也识别

## 执行流程
1. **数据采集**：用 findata-toolkit-us（yfinance + SEC EDGAR）拉取财务数据
   - 如果 yfinance 被限速，用 web_fetch 从 Google Finance / stockanalysis.com 拉取
2. **格雷厄姆分析**：基于 memory/investment_frameworks/security-analysis.md 的五关检验框架
3. **填充 JSON**：按 templates/equity-research/sample_input.json 的格式生成数据
4. **生成 PDF**：运行 `python3 templates/equity-research/generate_report.py input.json output.pdf --lang <lang>`
5. **发送**：通过 Telegram 发送 PDF 文件给用户

## 模板位置
- 脚本：templates/equity-research/generate_report.py
- 示例 JSON：templates/equity-research/sample_input.json
- 模板说明：templates/equity-research/TEMPLATE.md

## 注意事项
- 研报应当有充分的文字分析，不只是数据表格
- 每个章节的文字分析应有判断和批判性思维
- 风险部分不回避负面观点
- 报告通常 8-12 页
