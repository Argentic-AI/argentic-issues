# Argentic issues

The public place to report bugs and ask for features in Argentic: the engine, the client (`@argentic-ai/client`), `@argentic-ai/check`, and the getargentic.com site and platform.

Questions about setup or concepts? Start with the [docs](https://getargentic.com/docs/).

## Filing an issue

Use the bug or feature template. For a bug, the more of this you include, the faster it gets fixed:

- **Versions.** The engine version, and the client version if you're using it. Results we publish state the engine version, so we do the same here.
- **A minimal repro.** The smallest agent or call that still shows the problem, and the steps to get there.
- **What you saw and what you expected.** Error text is great, with secrets removed.
- **A run ID**, if the problem happened in a run. The ID is enough for us to look; don't paste the run's contents.

**This tracker is public.** Never paste API keys, model keys, run contents, customer data or account details. If you did by accident, edit the issue and rotate the key.

## What `confirmed` means

We read new issues. When we've triaged one and can reproduce it, we label it `confirmed`. Only confirmed issues appear on [getargentic.com/known-issues](https://getargentic.com/known-issues), as a title and a link back here. Issue bodies are never copied to the site.

No `confirmed` label doesn't mean we've ignored you. It means we haven't reproduced it yet, or it's a request rather than a bug.

## Security and private reports

Don't open a public issue for a security problem or anything involving keys or customer data. Email [hi@getargentic.com](mailto:hi@getargentic.com?subject=Security%20report). We'll reply, and we ask that you give us time to fix it before telling anyone else.

## Keeping it useful

Issues that are spam, abusive, or contain pasted secrets will be closed or removed.
