# CS249r: Tiny Machine Learning - Collaborative Book

[![All Contributors](https://img.shields.io/github/all-contributors/harvard-edge/cs249r_book?color=ee8449&style=flat-square)](#contributors)

Welcome to the collaborative book repository for students of CS249r: Tiny Machine Learning at Harvard! This repository
contains the source files of chapters and sections written by your peers. We're excited to see your contributions!

## Contributing

To contribute to the repository using pull requests, follow these steps:

1. **Fork the Repository**:
    - Navigate to the repository's GitHub page and click the 'Fork' button at the top-right corner.

2. **Clone Your Forked Repository**:
    ```bash
    git clone https://github.com/YOUR_USERNAME/cs249r_book.git
    ```

3. **Navigate to the Repository**:
    ```bash
    cd cs249r_book
    ```

4. **Set Upstream Remote**:
    ```bash
    git remote add upstream https://github.com/harvard-edge/cs249r_book.git
    ```

5. **Create a New Branch** for your chapter/section:
    ```bash
    git checkout -b name-of-your-new-branch
    ```

6. Write your chapter or section in Markdown.

7. **Commit Changes to Your Branch**:
    ```bash
    git add .
    git commit -m "Briefly describe your changes"
    ```

8. **Push Your Branch to Your Forked Repository**:
    ```bash
    git push origin name-of-your-new-branch
    ```

9. Navigate to your fork on GitHub and click the 'New pull request' button. Ensure you're comparing your branch from
   your fork to the `main` branch of the original `harvard-edge/cs249r_book` repository.

10. Submit the pull request with a descriptive message.

The instructors will assess your pull request and provide feedback. Once it's approved, your contribution will be
integrated into the `main` branch, and the book's website will be updated.

For a more detailed guide on the CS249r documentation process and peer review,
check [here](https://docs.google.com/document/d/1izDoWwFLnV8XK2FYCl23_9KYL_7EQ5OWLo-PCNUGle0).

---

## Website

The book's website is automatically constructed from the `gh-pages` branch. Once reviewed, changes to `main` are merged
into `gh-pages`.

You can view the book's website
at: [https://harvard-edge.github.io/cs249r_book/](https://harvard-edge.github.io/cs249r_book/)

---

## Local Rendering

For local rendering of the book, you need to have `quarto` installed. Once that's done, the following command can be
used to produce the HTML pages:

```bash
cd cs249r_book
quarto render
```

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ShvetankPrakash"><img src="https://avatars.githubusercontent.com/ShvetankPrakash?s=100" width="100px;" alt="Shvetank Prakash"/><br /><sub><b>Shvetank Prakash</b></sub></a><br /><a href="https=//github.com/harvard-edge/cs249r_book/commits?author=ShvetankPrakash" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jveejay"><img src="https://avatars.githubusercontent.com/jveejay?s=100" width="100px;" alt="Vijay Janapa Reddi"/><br /><sub><b>Vijay Janapa Reddi</b></sub></a><br /><a href="https=//github.com/harvard-edge/cs249r_book/commits?author=jveejay" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mpstewart1"><img src="https://avatars.githubusercontent.com/mpstewart1?s=100" width="100px;" alt="Matthew Stewart"/><br /><sub><b>Matthew Stewart</b></sub></a><br /><a href="https=//github.com/harvard-edge/cs249r_book/commits?author=mpstewart1" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/uchendui"><img src="https://avatars.githubusercontent.com/uchendui?s=100" width="100px;" alt="Ikechukwu Uchendu"/><br /><sub><b>Ikechukwu Uchendu</b></sub></a><br /><a href="https=//github.com/harvard-edge/cs249r_book/commits?author=uchendui" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://allcontributors.org) specification. Contributions of any kind are
welcome!