# Restuarant Reviews

A website reviewing the different restaurants visited as a couple.

Made with Hugo, using the [PaperMod](https://adityatelange.github.io/hugo-PaperMod/) theme

## Development

**Dependencies:** 

- Hugo
- Any text editor with `yaml` and `markdown` support

### Installing development environment

For my one and only collaborator

1. `cd restaurant_reviews`
2. `git submodule update --init --recursive`

## Contributing

Different pages are stored within the `content` directory.

I'm confused as to why I made a subdirectory called posts. I feel like I could omit that entirely.

To create a new article: 
- Ensure that `pwd` is the project root
- Run `hugo new content content/posts/reviews/<article_name>.md`
