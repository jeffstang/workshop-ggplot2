# Workshop: Introduction to ggplot2

An interactive workshop introducing ggplot2 data visualization to health sciences graduate students (no coding background required).

## 📋 Overview

This is a 40 minute presentation with 10-15 minutes for Q&A and interactive coding exercises. The workshop uses the gapminder dataset to demonstrate various ggplot2 capabilities including:

- Different geoms (scatter plots, line plots, bar plots, box plots)
- Aesthetics (color, size, shape, alpha)
- Layering multiple data representations
- Faceting (facet_wrap, facet_grid)
- Interactive coding with webR

## 🚀 Quick Start

### Viewing the Presentation

The presentation is built with Quarto and uses webR for interactive R code execution in the browser (no local R installation needed for participants!).

### Building the Presentation

If you have Quarto installed:

```bash
quarto render index.qmd
```

This will generate `index.html` which you can open in any web browser.

### Publishing

You can publish this presentation to:

- **GitHub Pages**: `quarto publish gh-pages`
- **Quarto Pub**: `quarto publish quarto-pub`
- **Netlify/Vercel**: Deploy the rendered HTML

## 📦 Requirements

**For building the presentation:**
- [Quarto](https://quarto.org/docs/get-started/) (version 1.4 or higher recommended)

**For participants:**
- Just a web browser! webR runs R code directly in the browser.

## 📚 Content Structure

The presentation covers:

1. **Introduction** (5 min)
   - Welcome and learning objectives
   - What is ggplot2 and why use it?

2. **Grammar of Graphics** (5 min)
   - Core concepts
   - Introduction to gapminder dataset

3. **Basic Plots** (15 min)
   - Scatter plots with aesthetics
   - Customization (color, size, transparency)
   - Interactive exercises

4. **Different Geoms** (10 min)
   - Line plots for time series
   - Bar/column plots for categories
   - Box plots for distributions

5. **Advanced Features** (10 min)
   - Layering multiple geoms
   - Faceting for small multiples
   - Themes and customization

6. **Practice & Applications** (5-10 min)
   - Health sciences applications
   - Practice exercises
   - Key takeaways

7. **Q&A and Interactive Coding** (10-15 min)

## 🎯 Learning Objectives

By the end of this workshop, participants will be able to:

- Understand the "grammar of graphics" concept
- Create basic plots with ggplot2
- Customize plot aesthetics
- Layer multiple data representations
- Create small multiples with faceting
- Apply these skills to health sciences data

## 🔧 Customization

### Modifying the Theme

Edit `custom.scss` to change colors, fonts, and styles.

### Adding Your Own Data

Replace the gapminder examples with your own dataset by:
1. Modifying the webR package list in the YAML header
2. Loading your data in code chunks
3. Updating the examples

### Adjusting Timing

The presentation is designed for 45-50 minutes. Adjust by:
- Skipping bonus slides (at the end)
- Reducing practice time
- Focusing on specific geoms relevant to your audience

## 📄 Files

- `index.qmd` - Main Quarto presentation file
- `custom.scss` - Custom styling
- `.gitignore` - Git ignore rules for build artifacts

## 🤝 Contributing

Suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.

## 📖 Resources

- [ggplot2 documentation](https://ggplot2.tidyverse.org/)
- [R for Data Science](https://r4ds.hadley.nz/)
- [Quarto documentation](https://quarto.org/)
- [webR documentation](https://docs.r-wasm.org/webr/latest/)
- [Gapminder data](https://www.gapminder.org/)

## 📝 License

This workshop material is available for educational use.
