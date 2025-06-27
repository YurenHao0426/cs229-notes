# CS229 Study Notes

A collection of concise LaTeX notes for Stanford CS229 Machine Learning course.

## 📚 Contents

### Current Notes (June 26, 2025)
- **Maximum Likelihood Estimation (MLE)** - Theory and definitions
- **Linear Regression** - Normal equation and gradient descent
- **Gradient Descent Example** - Step-by-step calculation with 3 data points
- **ML Framework** - Model → Algorithm → Parameters pipeline
- **Loss Functions** - Regression and classification examples
- **Model Complexity** - Bias-variance tradeoff with visualization
- **Generalization Error** - Continuous and discrete definitions with mathematical derivations

## 🗂️ Project Structure

```
cs229-notes/
├── 2025-06-26/                    # Daily notes folder
│   ├── 2025-06-26-notes.tex      # LaTeX source (7.4KB)
│   ├── 2025-06-26-notes.pdf      # Compiled PDF (4 pages, 270KB)
│   └── model-complexity-diagram.png  # Visualization diagram (100KB)
├── .vscode/                       # LaTeX Workshop configuration
│   └── settings.json             # Editor settings for LaTeX
├── template.tex                   # LaTeX template for new notes
├── template.pdf                   # Template example (2 pages)
├── main_notes.pdf                 # Additional reference material
└── README.md                      # This file
```

## 🛠️ Compilation

### Manual Compilation (Recommended)
```bash
cd 2025-06-26
pdflatex -interaction=nonstopmode 2025-06-26-notes.tex
```

### Using LaTeX Workshop (VS Code/Cursor)
- Configure LaTeX paths in `.vscode/settings.json`
- Use `Cmd + Option + B` to build

### Using the Template
1. Copy `template.tex` to your new date folder
2. Rename it (e.g., `2025-06-27-notes.tex`)
3. Update title and date in the document
4. Replace example content with your notes
5. Compile using the methods above

## 📖 Features

- **Concise Format** - Key concepts without excessive explanation
- **Mathematical Rigor** - Complete derivations with integrals and summations
- **Visual Aids** - Diagrams for complex concepts
- **Practical Examples** - Numerical calculations with real data
- **Organized Structure** - Daily folders for easy navigation
- **Optimized Layout** - Compact margins and spacing for efficient page usage
- **Ready-to-Use Template** - Pre-configured template with common structures

## 🔧 Requirements

- LaTeX distribution (BasicTeX/MacTeX)
- pdflatex and latexmk
- graphicx package for images

## 📝 Author

Yuren H

## 📅 Last Updated

June 26, 2025