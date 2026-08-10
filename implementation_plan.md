# SEO Keyword Optimization Plan

## Goal
Increase Google search visibility for the keywords: "Troy Su", "automate desktop troy", "PAD", "RPA", "Power Automate Desktop", and "無人值守".

## Current Issue
The site is brand new, so it naturally lacks domain authority compared to giants like Fortra. Additionally, much of the Chinese content is dynamically injected via JavaScript, and the fallback raw HTML lacks aggressive keyword targeting for "Troy Su" combined with "Power Automate Desktop".

## Proposed Changes

### 1. `index.html` (Home Page)
- **Title (`<title>`)**: Update to `<title>Troy Su | Power Automate Desktop (PAD) & RPA 無人值守專家 | Troy's Smart Automation</title>` to put "Troy Su" and the primary keywords at the very front.
- **Meta Description**: Update to aggressively target the keywords: "我是 Troy Su，專注於 Power Automate Desktop (PAD) 與 RPA 自動化。提供自行開發的 PAD Orchestrator，完美解決排程觸發與真正的無人值守 (Unattended) 需求。"
- **JSON-LD**: Ensure "Troy Su" is prominently listed in the WebSite schema.

### 2. `articles.html` (Insights Page)
- **Title (`<title>`)**: Update to `<title>技術文章與洞察 - Troy Su | Power Automate Desktop (PAD) & RPA 教學</title>`
- **Meta Description**: Include "Troy Su 分享關於 Power Automate Desktop, RPA, 無人值守與智慧家庭的技術文章與實務教學。"

### 3. `pad-unattended-guide.html` & `find-pad-id-guide.html` (Article Pages)
- **Title**: Append " | Troy Su 技術專欄" to the end of both titles.
- **Content**: Add a small author bio at the top or bottom of the raw HTML body (e.g. `<blockquote>作者：Troy Su | Power Automate Desktop (PAD) 專家</blockquote>`) so that Googlebot can easily parse the relationship between the author and the technical content without relying solely on JS.

### 4. `script.js` (Translations)
- Modify the `zh-TW` translation for `about_desc` to explicitly mention your name and expertise: "我是 Troy Su，我相信好的自動化..."
- Ensure `hero_intro` explicitly mentions RPA and PAD.

## Verification Plan
- Check the modified HTML files to ensure keywords are present in the raw source code.
- Provide instructions to the user to push the changes and request re-indexing in Google Search Console.
