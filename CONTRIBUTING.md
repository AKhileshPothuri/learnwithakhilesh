# Contributing

Contributions are welcome and appreciated. This book is better when more people catch errors, add nuance, and bring their own interview experience.

## What Makes a Good Contribution

- **Factual corrections** — wrong claim, outdated information, misleading analogy
- **Better explanations** — clearer prose, a stronger analogy, a missing intuition
- **Interview questions** — questions you've actually been asked or asked as an interviewer
- **Code improvements** — fixing bugs in code examples, adding a more idiomatic version
- **Missing topics** — important concepts that belong in a chapter but aren't covered

## What to Avoid

- Stylistic rewrites without a factual motivation
- Adding content to placeholder sections without proper depth (stubs are intentional)
- Changing the CC BY-NC license or attribution

## How to Contribute

1. **Fork the repo** and create a branch: `git checkout -b fix/transformer-attention-formula`
2. **Make your change** in the relevant `.qmd` file under `chapters/`
3. **Preview locally** with `quarto preview` to verify your change renders correctly
4. **Open a pull request** with a short description of what you changed and why

## Chapter File Structure

Each chapter follows this pattern:

```
# Chapter Title

::: {.callout-note}
**Who this chapter is for:** ...
**What you'll be able to answer:** ...
:::

## Section
[prose + code]

## Interview Questions
::: {.callout-tip title="Entry Level"} ... :::
::: {.callout-warning title="Mid Level"} ... :::
::: {.callout-important title="Forward Deployed Engineer"} ... :::

## Further Reading
```

Please preserve this structure when editing or adding sections.

## Local Setup

```bash
# Install Quarto: https://quarto.org/docs/get-started/
git clone https://github.com/AKhileshPothuri/learnwithakhilesh.git
cd learnwithakhilesh
quarto preview
```

## Questions

Open an issue if you're unsure whether a contribution fits. Happy to discuss.
