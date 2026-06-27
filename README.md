# Yank Note Notes

Personal notes managed with Yank Note and synchronized through Git.

## Structure

- `notes/` - Markdown notes.
- `assets/images/` - Images referenced by notes.
- `assets/files/` - Other attachments, such as PDFs, documents, archives, and exports.
- `templates/` - Reusable note templates.

## Suggested Link Style

Use relative paths in Markdown so notes render correctly both locally and on GitHub:

```md
![image](../assets/images/example.png)
[attachment](../assets/files/example.pdf)
```

If a note is inside a subfolder, adjust the relative path accordingly.
