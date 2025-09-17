# ai-template-proj-speckit

Sample prompt

```
/specify Build a web application that can help me organize my photos in separate photo albums. Albums are grouped by date and can be re-organized by dragging and dropping on the main page. Albums are never in other nested albums. Within each album, photos are previewed in a tile-like interface.

/plan This app uses nuxt js. Use TypeScript and HTML and CSS. The web app should look super clean and minimalistic.

/tasks
```

## Install

```bash
# install ux
curl -LsSf https://astral.sh/uv/install.sh | sh

# install spec-kit
uvx --from git+https://github.com/github/spec-kit.git specify init <PROJECT_NAME>
# or
uvx --from git+https://github.com/github/spec-kit.git specify init --here
```

## Resources

- [GitHub’s Spec-Kit Will CHANGE How You Code Forever (Full Tutorial)](https://www.youtube.com/watch?v=xfyec__ieHA)
