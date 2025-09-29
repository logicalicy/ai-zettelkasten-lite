# AI Zettelkasten (Lite)

Lightweight AI-powered Zettelkasten-inspired knowledge management system. Get started in minutes with Claude Code and Pinecone DB.

# Getting started

1. Save [`ai-zettelkasten-prompt.md`](./ai-zettelkasten-prompt.md) to your local machine
2. Add Pinecone MCP to Claude Code
3. Create `zettelkasten-db` index in [Pinecone DB](https://app.pinecone.io/)
4. Add a quote to your Zettelkasten. Type into Claude Code:
  > Please read /path/to/ai-zettelkasten-prompt.md and give me some Jim Rohn quotes in a numbered list. Then, I will tell you which ones to include in pinecone
5. Choose a few quotes to add to your knowledge base
6. Ask it to retrieve a quote. Type into Claude Code:
  > Ok give me a Jim Rohn quote about discipline
7. Add a link/bookmark to your Zettelkasten. Type into Claude Code:
  > Please add this to my Zettelkasten https://www.bbc.co.uk/news/articles/some-article
8. Ask it to retrieve a bookmark. Type into Claude Code:
  > Can you show me my bookmarks
9. Add a task. Type into Claude Code:
  > Add task to make a todo app prototype, set its status to "to do"
10. Ask it to retrieve tasks. Type into Claude Code
  > Show my kanban board filtered by todo tasks

# Alias commands

Need to quickly add something to your Zettelkasten or query it quickly? 

Add `.zettelkastenrc` to your `.bashrc`, `.zshrc`, etc. and run:

```
# Quick capture
zadd "Spaced repetition works best with expanding intervals"

# Search by meaning, not keywords
zsearch "techniques for better memory retention"

# Bookmark a URL instantly
zbookmark https://example.com/article

# View tasks
zboard "in-progress"
```
