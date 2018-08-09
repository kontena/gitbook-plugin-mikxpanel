# Mikxpanel tracking for GitBook

Install and configure mikxpanel plugin at `book.json`:

```
{
    plugins: ["mikxpanel@git+https://github.com/kontena/gitbook-plugin-mikxpanel.git"],
    pluginsConfig: {
        "mikxpanel": {
            "token": "my mixpanel token",
            "event_prefix": "docs"
        }
    }
}
```
