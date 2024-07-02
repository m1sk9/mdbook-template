# mdbook-template

Documentation templates using rust-lang/mdbook.

## Features

- Using [rust-lang/mdbook](https://github.com/rust-lang/mdbook) to generate documentation.
- Some included rust-lang/mdbook third-party plugins:
  - [slowsage/mdbook-pagetoc](https://github.com/slowsage/mdbook-pagetoc): Add a table of contents to each page.
  - [lambdalisue/rs-mdbook-alerts](https://github.com/lambdalisue/rs-mdbook-alerts): Add GitHub Flavored Markdown's Alerts to your book.

### mdbook-pagetoc

Add a table of contents to each page.

```markdown
<!-- toc -->
```

### rs-mdbook-alerts

Add GitHub Flavored Markdown's Alerts to your book.

```markdown
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
```

## Usage

1. Click the `Use this template` button to create a new repository.
2. Clone the repository to your local machine.
3. Install `mdbook` by running `cargo install mdbook`.
4. Install the `mdbook-pagetoc` and `rs-mdbook-alerts` plugins by running `cargo install mdbook-pagetoc mdbook-alerts`.
5. Run `mdbook serve` to preview the documentation.
6. Edit the `book.toml` file to customize the documentation.

## License

mdbook-template is distributed under the MIT License. See [LICENSE](LICENSE) for more information.

- mdbook: [`Mozilla Public License 2.0`](https://github.com/rust-lang/mdBook/blob/master/LICENSE)
- mdbook-pagetoc: [`Mozilla Public License 2.0`](https://github.com/slowsage/mdbook-pagetoc/blob/master/LICENSE)
- rs-mdbook-alerts: [`MIT License`](https://github.com/lambdalisue/rs-mdbook-alerts/blob/main/LICENSE)
