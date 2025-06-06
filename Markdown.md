# **Markdown 简介**  
Markdown 是一种轻量级标记语言，由 **John Gruber** 和 **Aaron Swartz** 于 2004 年创建。它通过简单易写的语法将纯文本转换为 HTML 或其他格式，兼顾可读性和高效排版。以下是常用语法说明：

---

### **基础语法**
1. **标题**  
   用 `#` 表示标题级别（1-6 级）：
   ```markdown
   # 一级标题
   ## 二级标题
   ### 三级标题
   ```

2. **文字强调**  
   - *斜体*: `*文本*` 或 `_文本_`  
   - **粗体**: `**文本**` 或 `__文本__`  
   - ~~删除线~~: `~~文本~~`（非标准语法，但多数平台支持）。

3. **列表**  
   - 无序列表：
     ```markdown
     - 项目1
     - 项目2
       - 子项目（缩进两个空格）
     ```
   - 有序列表：
     ```markdown
     1. 第一项
     2. 第二项
     ```

4. **链接与图片**  
   - 链接: `[显示文字](https://example.com)`  
   - 图片: `![图片描述](image.jpg)`

5. **代码**  
   - 行内代码: `` `代码` ``  
   - 代码块（支持语法高亮）：
     ````markdown
     ```python
     print("你好，世界！")
     ```
     ````

6. **引用块**  
   `> 这是一段引用内容。`

7. **分割线**  
   `---` 或 `***`

8. **表格**（扩展语法）:  
   ```markdown
   | 列1     | 列2     |
   |---------|---------|
   | 第一行 | 数据    |
   | 第二行 | 数据    |
   ```

---

### **示例文档**
**Markdown 输入**:
```markdown
# Markdown 入门指南

一种*简单*的**文本格式化**方法。

## 主要功能
- 易读易写
- 可转换为 HTML
- 支持 `代码` 片段

访问 [GitHub](https://github.com) 了解更多。

> "简洁至上。"
```

**渲染效果**：  
![Markdown 效果示意图](https://via.placeholder.com/400x200?text=模拟渲染效果)

---

### **注意事项**
1. **兼容性**：不同平台（如 GitHub、语雀）可能支持扩展语法（如任务列表、流程图）。  
2. **转义字符**：用 `\*` 显示原符号（如 `\*非斜体\*`）。  
3. **换行**：行尾加两个空格可强制换行。  

Markdown 广泛用于文档编写、技术博客、项目 README 和笔记整理，尤其适合快速排版！ ✨