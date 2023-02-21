# Contributing Guidelines

Here are guidelines for contributing.

## Project structues

There's directory `src/` which contains translated documents. There's `src-English/` which contains original documents.

## Translating words and paragraphs

1. Avoid Lexicalization
2. Avoid Tokiponizing generic terms. For example, translating *linker* into *ilo Linka*.

### Leaving out terms

This is out of laziness on my part but you may leave out terms in toki pona translation if you think it doesn't matter:

- You may leave out terms if mentioning other terms work. For example: The original Rust book mentions Linker is needed for Rust to work. However, in toki pona, there's no mention of linker because linker is part of C compiler and Rust needed C compiler anyway.
- With assumptions to the reader, you may leave out terms if the readers knows it anyway. For example, the original Rust book mentions the reader must be familiar with command-line. However, one prerequisites of the Rust book is that the reader must know at least one programming languages. Given this prerequisite, we can remove the mention of knowledge command-line being a requirement.

### Avoid lexicalization

- Avoid just translating *computer* to *ilo nanpa*. Computers are more than *ilo nanpa*. It can be *ilo pali* as well, it can be *ilo sitelen*. With the right context, we can just refer to it as just *ilo*. This "right context" happens to all throughout the book as we're dealing with programming.
- When not in context. Explain newly encountered words in sentences, but keep it brief. here's few example:
  - **Internet:**

    Original:

    > The first step is to install Rust. We’ll download Rust through `rustup`, a command line tool for managing Rust versions and associated tools. You’ll need an _internet connection_ for the download.

    Translated:

    > pali nanpa wan li ni: o lon e nasin Wasa lon ilo sina kepeken ilo rustup. ilo `rustup` li lon e ilo mute pi nasin Wasa. ni la _ilo sina o ken toki tawa ilo ante_.

  - **Password**

    Original:

    > The command downloads a script and starts the installation of the rustup tool, which installs the latest stable version of Rust. You might be prompted for your _password_. (&#8230;)

    Translated:

    > kepeken toki ni la ilo rustup li kama lon. ken la, _sina wile toki len. kepeken toki len ni la ilo sina li ken sona e ni: jan ilo li sina._

We have English to toki pona dictionary just for this purpose: [lipu sona][lipu-sona].

### To Tokiponize or not to Tokiponize

I'm honestly not sure for most part. But, here are the ones I recommend:

- Don't Tokiponize generic words like linker and password, use the techniques explained in [section Avoid lexicaliation][avoid-lexicalization].
- Don't Tokiponize command-line tool name or other words that are expected in command or program such as programming keyword. Wrap them in `` ` ` ``. For example: ilo `cargo`, ilo `rustup`, nimi `if`, and nimi `false`.

[lipu-sona]: ./lipu-sona.md
[avoid-lexicalization]: #avoid-lexicalization
