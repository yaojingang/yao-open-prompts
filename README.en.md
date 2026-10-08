# Yao Open Prompts

[English Prompt Library](prompts-en/README.md) · [Web Navigation](https://yaojingang.github.io/yao-open-prompts/) · [GitHub Repository](https://github.com/yaojingang/yao-open-prompts)

Yao Open Prompts is an open-source bilingual prompt library for prompt engineering, practical AI work, learning, content creation, marketing, and everyday scenarios.

The main repository is organized around the Chinese prompt library. This English README is the entry point for the full English mirror.

## English Prompt Library

**[136 English Prompts](prompts-en/README.md)**: one English file for every Chinese prompt file in `prompts/`, using the same relative path under `prompts-en/`.

Each English prompt is stored as an independent Markdown file and points back to its matching Chinese source file through the `source_section` frontmatter field.

## Featured Prompt

**[Intelligent Meta-Prompt Design and Optimization System V1.0](prompts-en/01-ai-methods/rtf-meta-prompt-system-v1.md)**: a bidirectional prompt compiler that generates prompts from requirements and diagnoses, restructures, and optimizes existing prompts. It includes deployment adaptation, evidence-based quality review, boundary controls, and design-level static testing.

## Book companion collection

**[Course Marketing: 17 companion prompts](prompts-en/08-ai-marketing/course-marketing/README.md)** by Yao Jingang covers positioning, design, sales, and operations. The [interactive navigator](https://yaojingang.github.io/yao-open-prompts/course-marketing.html?lang=en) supports search, filtering, editing, copying, and offline HTML downloads. See the [usage guide](references/course-marketing-guide.en.md) for inputs, outputs, follow-up questions, and the source note about duplicate chapters 3.5 and 2.6.

## Directory

```text
prompts-en/
  README.md
  01-ai-methods/
  02-ai-work/
  03-ai-learning/
  ...
  06-ai-content/
    README.md
    hook-opening-copy.md
  08-ai-marketing/
    README.md
    geo-article-ai-friendly-transformation.md
    geo-compliance-risk-management.md
```

## How To Use

1. Open [English Prompt Library](prompts-en/README.md).
2. Choose the prompt that matches your task.
3. Copy the `Prompt` section.
4. Replace `{{user_information}}` with your task details.
5. Run it in your preferred AI model and iterate for your platform, audience, and tone.

## Maintenance

English prompts are kept in `prompts-en/` so they do not mix with the Chinese source library. Keep the same relative path as the Chinese source file and run `python3 scripts/check_repo.py` before publishing.

After editing this collection, rebuild its page with `python3 scripts/generate_course_marketing.py` and refresh English directories with `python3 scripts/generate_english_readmes.py`.
