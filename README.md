# MLeRP Documentation
This repo is to house the documentation for MLeRP. The documentation uses the Quarto framework to render the documentation hosted at `https://docs.mlerp.cloud.edu.au/` using GitHub Pages. The documentation is also published on Confluence in the [`Machine Learning eResearch Platform Knowledge Base`](https://monasheresearch.atlassian.net/wiki/spaces/MLeRPKB/overview).

The pages are written in quarto markdown for main pages, with iPython notebook tutorials where appropriate.

## Website Publishing
The HTML that is rendered is hosted on the `gh-pages` branch. To render it run:

To publish:
1. Set the project type to confluence in `_quarto.yml`
2. Then run: `quarto publish gh-pages`
3. Push to the [GitHub repo](https://github.com/mitchellshargreaves-monash/MLeRP-Documentation) if its not your main remote

For more information look at [Quarto's GitHub Pages documentation](https://quarto.org/docs/publishing/github-pages.html).

## Confluence Publishing
On the first time that you publish, Quarto will prompt you for the Confluence space, your email and API token. The space is then stored in `_publish.yml` to avoid reprompting every publish.

To publish:
1. Set the project type to confluence in `_quarto.yml`
2. Then run: `quarto publish confluence`
  
For more information look at [Quarto's Confluence documentation](https://quarto.org/docs/publishing/confluence.html).