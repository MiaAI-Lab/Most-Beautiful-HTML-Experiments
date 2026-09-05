# Mia’s Most Beautiful HTML Experiments

An archive of the most beautiful HTML files language models can make.

One prompt. One model. One self-contained `.html` file. No frameworks, no build
step, no post-editing by human hands — whatever survives the look gets archived.

**Live at:** <https://miaai-lab.github.io/Most-Beautiful-HTML-Experiments/>

## The prompt

Every entry receives this sentence, verbatim:

> “Create the most beautiful HTML file you could think of. Something that when people
> see it, all they can say is _WOW!!!_ It must be visually impressive, beautiful, and
> just music to the eyes. Be thorough, but creative. Don't make mistakes.”

## The collection

| №   | piece                                 | model                                     | file / home                                       |
| --- | ------------------------------------- | ----------------------------------------- | ----------------------------------------------- |
| 001 | **PRISM — a study in light**          | GPT 6.0 Astra _(high effort)_             | `astra-high.html`                                |
| 002 | **Synesthesia — a fluid you can hear** | Claude Fable 5.1 _(high effort)_          | [Claude-Fable-5.1-Beautiful-HTML](https://github.com/MiaAI-Lab/Claude-Fable-5.1-Beautiful-HTML) · [live](https://miaai-lab.github.io/Claude-Fable-5.1-Beautiful-HTML/) |
| 003 | **AETHER — a cathedral of pure mathematics** | Ox Alpha                          | [Ox-Alpha-Beutiful-HTML](https://github.com/MiaAI-Lab/Ox-Alpha-Beutiful-HTML) · [live](https://miaai-lab.github.io/Ox-Alpha-Beutiful-HTML/) |
| 004 | _reserved — next model in line_      | —                                         | —                                                |

## The rules

1. **One prompt, unchanged.** No steering, no follow-ups, no “please make it prettier”.
2. **One file, self-contained.** Markup, style, motion and fonts all live in the document.
   Copy it to a stick, lose the internet, and it still performs.
3. **Nobody's blind.** Results are published raw and dated, so you can hold a model's
   taste against your own.

## Adding an entry

1. Drop the model's file in the root of the repo, named after the model, e.g. `model-effort.html`.
2. In `index.html`, duplicate the `№ 001` blocks — the `<article class="piece">` in
   `#collection` and the `<a class="row">` in `#ledger` — and update the number, title,
   model name and filename.
3. An entry does not have to live in this repo. 002 and 003 are each a single file in their own
   repository, served by their own Pages site — the archive simply links out to them.
3. Push. GitHub Pages serves it from the root of `main`; no build configuration needed.

## Notes

- `index.html` and every entry are static documents. Pages needs no workflow, no action, no
  dependencies — there is nothing to install.
- No cookies, no trackers, no analytics.
- The archive opens in a **light** (paper) theme; a switch in the masthead offers the original night
  theme. It is a plain checkbox styled with `:has()`, so there is still no script anywhere in the page.
  Because it is script-free the choice does not persist across reloads — light is the door every time.

Follow along on X: [@MiaAI_lab](https://x.com/MiaAI_lab).

Maintained by [MiaAI Lab](https://github.com/MiaAI-Lab).
