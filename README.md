# GEO prompt templates

Buyer-intent prompt templates and a simple tracking sheet for measuring how often your brand appears in AI-generated answers, sometimes called **share of answers**, share of voice or Share of Model.

Maintained by [Aurum Digital](https://aurumdigital.org).

## How to use

1. **Build your prompt set.** Copy [`prompts.csv`](prompts.csv) and replace the placeholders (`[category]`, `[brand]`, `[competitor]`, `[use case]`, `[city]`) with your own. Aim for 20 to 50 prompts that reflect real buyer questions at each stage of the decision.
2. **Run the same prompts on each platform:** ChatGPT, Gemini, Google AI Overviews or AI Mode, Perplexity, Claude and Copilot. Use a fresh session and note the date, platform and any settings (for example, whether web search was on).
3. **Record the results** in [`tracking-template.csv`](tracking-template.csv): whether your brand was mentioned, its position, whether the description was accurate, which competitors appeared and which sources were cited.
4. **Calculate share of answers:** answers that mention your brand divided by total answers, per platform and overall.
5. **Repeat monthly.** AI answers vary between runs, so trends across several measurements matter more than any single result.

The **cited sources** column is often the most useful: it shows which publications, review sites and pages AI assistants trust in your market, and where digital PR and content work will have the most effect.

## Prompt types

| Type | What it tells you |
|---|---|
| Category | Whether you make the shortlist for your main category |
| Problem | Whether you are recommended for the problems you solve |
| Comparison | How you are positioned against named competitors |
| Brand | Whether the facts AI states about you are accurate |
| Local or market | Whether you appear in each market you serve |

## Learn more

- [What is Generative Engine Optimization?](https://aurumdigital.org/insights/what-is-generative-engine-optimization/)
- [The GEO measurement loop (diagram, CC BY 4.0)](https://aurumdigital.org/resources/geo-diagrams/)

## License

Content in this repository is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit Aurum Digital with a link to https://aurumdigital.org.
