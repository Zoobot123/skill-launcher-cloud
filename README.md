# Skill Launcher Cloud

A static page for managing my Claude skills from a phone, with the PC off. It holds only the page code: no skills and no token.
It talks to two private repos through the GitHub API, using a token kept in the visitor's own browser:

- `Zoobot123/manga-skills` - the NovelAI skills.
- `Zoobot123/claude-skills` - every other skill.

Make a fine-grained token with access to both repos and Contents: read and write. The Both / NovelAI / Claude buttons filter the list,
and a skill's Triggers tab (Repo) or its info box moves it to the other repo. Agents: read `llms.txt`.
