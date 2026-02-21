# RepNet Intelligence Repository - Project Mandates

## Dossier Structure
Every dossier file (e.g., `dossier-*.html`) **MUST** include a "Back to Repositories" navigation link at the top of the `<main>` container, matching the following structure and styling:

```html
<nav class="mb-4">
    <a href="index.html#repositories" class="flex items-center gap-2 text-xs font-bold uppercase tracking-widest text-zinc-500 hover:text-blue-400 transition-all group">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 transition-transform group-hover:-translate-x-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18" />
        </svg>
        Back to Repositories
    </a>
</nav>
```

## Index Integration
When adding a new person to `index.html`:
1.  Insert the new card in **alphabetical order** by Name.
2.  Use the `dossier-card` class and ensure the card links correctly to the dossier HTML file.
3.  Include a concise summary (approx. 2 lines) that reflects the risk level and key takeaway from the dossier.
