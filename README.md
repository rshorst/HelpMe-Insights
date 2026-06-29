Seam-ful AI

An interactive companion for understanding how HelpMe — the course's AI assistant — actually works, by looking at where it breaks. Built for ETEC 531 from the cohort's Move 1 audits of HelpMe.

The proposition

HelpMe can't out-muscle ChatGPT or Claude, and it shouldn't try. A course is optimised for understanding, not output, and for that a tool you can see through beats a more capable one you can't. RAG matters because retrieval is the one layer of the AI stack whose seams you can actually inspect — the chunks, the citations, what got pulled and what got left out. Visible weakness is where understanding gets built — judgment you then carry into the seamless tools whose weaknesses you'll never get to see.

What's inside

Watch it pull — and drop — a retrieval simulator. Type a query, slide the top-k, and watch which sources get retrieved and which silently fail.
Six things it isn't doing — flip cards pairing a common misconception with the mechanism underneath.
It didn't "choose" — rewriting the human verbs we use for AI into what is mechanically happening.
Prompts that earn their keep — the prompting moves to keep, and the ones to build next.
Why retrieve at all? — RAG vs. long context, and the trade-off.
How this was made — a plain account of the process.


Use it

It is a single self-contained HTML file — no build step, no dependencies. Open index.html in any browser, or visit the hosted page.

To embed it in Canvas, add this to a page via the HTML editor:

html<iframe src="https://<username>.github.io/<repo>/" width="100%" height="1400" style="border:0"></iframe>

If the iframe shows blank, your Canvas instance may block github.io embeds — link to the URL directly instead.

Credits

Built with Claude Cowork. Concept, framing, and design: Rachel Horst and ETEC 531 2026S students.

Reuse and adapt freely.
