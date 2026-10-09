# Byte Open Door

A clickable prototype of the Byte recipient page, built for the Digital Harbor Business Media growth exercise (October 2026).

It shows what a person sees when a Byte link lands in their inbox: no login, two actions (Got it, Question at a timestamp), and a name-and-email step the first time they act. You can ask a question, have the sender answer with a Byte, and watch the prompt appear that turns a viewer into a sender. Turn on **Show instrumentation** to see which event fires at each element; the log at the bottom records them with the properties the warehouse would receive, and the plan beneath it lists the event schema and the five dashboard numbers.

Every count on the page is an example. The sender, Jordan, is fictional.

## Run it

Open `index.html` in a browser. There is no build step and no dependency beyond two Google Fonts.

## Deploy

Static site. On Vercel, import the repo and deploy with the defaults (no framework, no build command, output directory `.`).
