---
title: How to style your Quarto/R Markdown code chunks in RStudio
category: note
format: list
feed: hide
date: 2025-09-24
---

In RStudio when you’re writing a Quarto (`.qmd`) or R Markdown (`.Rmd`) document, the code chunks themselves are not automatically “tidyverse-styled.” What you might want is to have the code inside the chunks formatted according to the [tidyverse](https://style.tidyverse.org/) style guide.

Here’s how you can set that up:

## 1. Set up the `styler` package

### 1.1. Install the `styler` package

```{r}
install.packages("styler")
```

### 1.2. Style code chunks in your document

In RStudio, you can style all code chunks in your `.qmd`/`.Rmd` file by running

```{r}
styler::style_file("your_file.Rmd")
```

or style only the highlighted lines of code by running

```{r}
styler:::style_selection()
```

### 1.3. Example

Before styling:

```{r}
library(dplyr)
df%>%group_by(species)%>%summarise(avg=mean(sepal_length))
```

After styling:

```{r}
library(dplyr)

df %>%
  group_by(species) %>%
  summarise(avg = mean(sepal_length))
```

## 2. Set up `styler` shortcut in RStudio (Optional)

### 2.1. Open Keyboard Shortcut editor in RStudio

In RStudio, go to *Tools* -> *Modify Keyboard Shortcuts...*. A searchable dialog should appear.

### 2.2. Find the `styler` actions

Search for "style" in the search bar. You should see actions like *Style active file*, *Style selection*, etc.

### 2.3. Bind shortcuts to actions

Click the *Shortcut* column in the corresponding row and press the key combination you want to use (e.g., `Alt/Option + Shift + F` for matching VS Code). Make sure the shortcut is not already in use.

## LLM Usage Disclosure

| **Model** | **Organization** | **Date** |
|-----------|------------------|----------|
| [GPT-5](https://openai.com/gpt-5/) | OpenAI | September 2025|

This content was created with assistance from the above-mentioned large language model(s). All information has been reviewed and verified by the author.
