---
name: get-started
description: Connect to SeoVision and see where a project stands. Use when the person has just added SeoVision, asks what SeoVision can do for their site, or wants a quick status of their project.
---

# Get started with SeoVision

SeoVision helps a website rank in search and get cited by AI assistants. It runs site audits, tracks how often AI assistants name the brand, writes and publishes articles to the site, and places backlinks. This workflow checks the connection and gives the person a short status of their project.

1. Call `seovision_list_projects`.
   - If the call asks for a sign-in, ask the person to finish the SeoVision sign-in that opened in their browser, then call it again.
   - If no project is listed, tell the person that SeoVision shows the projects of an active SeoVision account, which they manage at https://app.seovision.io. Stop there.
   - If one project is listed, use it. If several are listed, show their domains and status and ask which one to work on.
   - Pass that project's `projectId` to every call that follows.
2. Call `seovision_get_overview` and summarize it in plain words: how visible the site is in search and in AI answers, what SeoVision did lately, and anything that waits for the person.
3. Call `seovision_get_setup_progress`. If setup is not finished, name the next step and offer to help with it. If it says the onboarding is not finished, call `seovision_get_onboarding` to see which step comes next.
4. End with three questions the person can ask next, for example "What should I fix first on my site?", "How visible is my brand in AI answers this month?" and "Write my weekly SEO report."

Keep the answer short. Read calls change nothing. A call that publishes to the live site, deletes, or spends credit returns a preview first: show the preview, wait for a clear yes in the chat, then call again with `confirm: true`.
