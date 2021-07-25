Simple reproduction for a bug in [Astro](https://github.com/snowpackjs/astro) where markdown code blocks are syntax highlighted when they’re written directly inside the `<Markdown></Markdown>` component, but not when it’s a markdown string passed into the `content` prop `<Markdown content={content} />`.

The demo is in [src/pages/index.astro](src/pages/index.astro).
