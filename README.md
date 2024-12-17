You can download the template on [AnkiWeb](https://ankiweb.net/shared/info/356679663)

### Card Template Description

This is an **Anki card template** designed with HTML, CSS, and JavaScript. It features an interactive, user-friendly format with support for cloze deletions and dynamic content display. Below is a breakdown of the template's components and functionality.

<img width="600" alt="Snipaste_2024-12-17_21-45-48" src="https://github.com/user-attachments/assets/a1968f5a-0901-41db-8352-49b1c825ea85" />

<img width="600" alt="Snipaste_2024-12-17_21-45-29" src="https://github.com/user-attachments/assets/8c7e5617-80b3-4733-a465-ca91e62d512f" />

#### **Front Side (Question)**

- **Question Layout**: The front of the card contains the question, displayed in a central location. The text is styled to be readable and visually appealing.
- **Interactive Features**:
  - **Cloze Deletion**: Words or phrases enclosed in `{{ }}` can be clicked to reveal a hidden answer, allowing users to fill in the blanks.
  - **Information Pop-ups**: Text enclosed in `[ ]^( )` triggers a pop-up with additional information when clicked.
  
- **JavaScript Functions**:
  - **`toggleInfo()`**: Displays and hides the information pop-ups. The position of the pop-up is dynamically adjusted based on the viewport.
  - **`toggleCloze()`**: Allows the user to interact with cloze deletions. Clicking on the blank area makes it editable. The correct answer is displayed in green, and incorrect answers are shown in red.
  
#### **Back Side (Answer)**

- **Answer Layout**: The back of the card shows the answer and any supplementary tips. Similar to the front side, the content can include cloze deletions and informational pop-ups.
- **Tips Section**: If any tips are provided in the card data, they will be displayed here with a distinct style.

#### **CSS Styling**

- **Basic Styling**: The card is designed with a clean and minimalist aesthetic. The text is readable, with sufficient contrast and line spacing.
- **Night Mode**: A dark theme that adjusts the background and text colors for easier reading in low-light environments.
- **Fonts**: Custom fonts are included for a unique, aesthetic look.

#### **JavaScript Behavior**

- **Dynamic Interactivity**: The card's interactive features (cloze deletions and pop-up information) are handled using JavaScript. These interactions make the card content more engaging and useful for active recall.
- **Animation**: The back side of the card appears with a smooth slide-in animation.

---

### 卡片模板描述

这是一个基于 **HTML**、**CSS** 和 **JavaScript** 制作的 **Anki 卡片模板**，设计上注重交互性和易用性，支持填空（Cloze）和动态内容展示。以下是模板的各个组成部分和功能描述。

#### **正面（问题）**

- **问题布局**: 卡片的正面展示问题，内容居中，文字清晰易读，视觉效果良好。
- **交互功能**:
  - **填空（Cloze）**: 用 `{{ }}` 包裹的词语或短语可以点击显示隐藏的答案，帮助用户进行填空练习。
  - **信息弹窗**: 用 `[ ]^( )` 包裹的文字点击后会弹出额外信息，方便用户进一步了解相关内容。
  
- **JavaScript 功能**:
  - **`toggleInfo()`**: 用于显示和隐藏信息弹窗，弹窗的位置会根据页面宽度自动调整。
  - **`toggleCloze()`**: 允许用户与填空部分互动。点击后会进入可编辑状态。正确答案显示为绿色，错误答案显示为红色。
  
#### **背面（答案）**

- **答案布局**: 卡片的背面展示答案以及任何附加的提示。和正面一样，背面内容也可以包含填空和信息弹窗。
- **提示部分**: 如果卡片数据中包含提示，提示会以不同的样式展示。

#### **CSS 样式**

- **基础样式**: 卡片采用简洁而现代的设计，确保文本清晰易读，并具有适当的对比度和行间距。
- **夜间模式**: 提供深色主题，调整背景和文本颜色，便于低光环境下阅读。
- **字体**: 使用自定义字体来增加卡片的独特视觉效果。

#### **JavaScript 行为**

- **动态交互**: 卡片的交互功能（如填空和信息弹窗）通过 JavaScript 处理。这些交互功能使得卡片内容更加生动，促进主动回忆。
- **动画效果**: 卡片背面会以平滑的滑入动画展示，增加用户体验的流畅感。
