# AI-readiness checklist for small business websites

Twelve checks that decide whether ChatGPT, Gemini, Claude and Perplexity can find and read a small business's website. Each check links to the assistants' own documentation or to a public study.

**Use it:** https://botofmouth.github.io/ai-readiness-checklist/ (English) · https://botofmouth.github.io/ai-readiness-checklist/es/ (español)

Tick the boxes as you go. Your ticks are saved in your browser only. Nothing is sent anywhere.

## The checks

**Can AI assistants reach your site?**
1. Your `robots.txt` doesn't block the AI search crawlers: OAI-SearchBot, Claude-SearchBot, PerplexityBot, Googlebot. ([OpenAI](https://platform.openai.com/docs/bots))
2. Your firewall or CDN doesn't block them either.
3. Google can index your main pages. ([Google](https://developers.google.com/search/docs/appearance/ai-features))

**Can they read what matters?**

4. Your key facts are plain text on the page. ([Google](https://developers.google.com/search/docs/appearance/ai-features))
5. Those facts show up without JavaScript. ([Vercel](https://vercel.com/blog/the-rise-of-the-ai-crawler))
6. No template leftovers, fake badges or placeholder reviews.

**Do your facts agree everywhere?**

7. Your Google Business Profile is complete and current. ([Google](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide))
8. Name, address and phone match on every listing.
9. You earn real reviews and reply to them.

**Nice to have**

10. Structured data repeats the same facts as the page.
11. An `llms.txt` file, if you like. ([llmstxt.org](https://llmstxt.org/))

**Then check the answers**

12. Ask the assistants yourself, more than once, on different days. ([SparkToro](https://sparktoro.com/blog/new-research-ais-are-highly-inconsistent-when-recommending-brands-or-products-marketers-should-take-care-when-tracking-ai-visibility/))

Nobody can guarantee that an AI assistant will name a business. These checks make sure the facts are there when it looks.

## Files

- `index.html`: the checklist in English
- `es/index.html`: the checklist in Spanish
- `og.png`, `favicon.png`: images
- `.nojekyll`: serve the files as they are

One static page with no build step and no dependencies.

## Contributing

Spotted something out of date? Open an issue or a pull request, with a link to the source.

## License

Text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Made by [BotOfMouth](https://botofmouth.com).
