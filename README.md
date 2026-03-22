## Helios Space - Technical Blog

Welcome to the source repository for [Helios Space](https://yukishama9.github.io/Helios-Blog/), a technical blog by Helios Shen.

### 📝 About

This is a Jekyll-powered blog hosted on GitHub Pages. Posts are written in Markdown and automatically published when pushed to this repository.

### ☕ Support this project
[![Support my work](https://img.shields.io/badge/Support-Buy%20me%20a%20coffee-orange?style=for-the-badge)](https://yukishama9.github.io/Helios-Blog/)


### 🚀 How to Write a New Post

Writing a new blog post is simple:

1. **Create a new file** in the `_posts/` directory with this naming format:
   ```
   YYYY-MM-DD-post-title.md
   ```
   Example: `2026-04-15-understanding-rust-ownership.md`

2. **Add Front Matter** at the top of your file:
   ```markdown
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS +0800
   categories: [category1, category2]
   tags: [tag1, tag2]
   ---
   ```

3. **Write your content** in Markdown below the Front Matter:
   ```markdown
   # Your heading
   
   Your paragraph text here.
   
   ```python
   # Code blocks with syntax highlighting
   def hello():
       print("Hello, World!")
   ```
   ```

4. **Commit and push** to the repository:
   ```bash
   git add _posts/2026-04-15-understanding-rust-ownership.md
   git commit -m "Add post: Understanding Rust Ownership"
   git push origin main
   ```

GitHub Pages will automatically rebuild and publish your post within a minute.

### 📁 Repository Structure

```
.
├── _config.yml          # Site configuration (title, theme, plugins)
├── _posts/              # All blog posts (Main content folder)
├── index.md             # Home page (auto-lists all posts)
├── about.md             # About page
├── README.md            # This file
└── .gitignore           # Git ignore rules (optional)
```

### ✨ Features

- **Automatic Post Listing**: The home page automatically shows all posts in reverse chronological order
- **Syntax Highlighting**: Code blocks are automatically highlighted
- **RSS Feed**: Readers can subscribe to new posts via `/feed.xml`
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **About Page**: Navigation link to your about page

### 🏠 Site Pages

- **Home**: `/` - Lists all blog posts
- **About**: `/about/` - About the author
- **Post Archives**: Posts are archived by date and accessible via the home page

### 🔧 Site Configuration

Edit `_config.yml` to customize:
- `title`: Blog title
- `description`: Blog description
- `author`: Your name
- `github_username`: Your GitHub username (adds a link in the footer)

### 📚 Markdown Tips

- **Bold**: `**text**`
- **Italic**: `_text_` or `*text*`
- **Code**: Inline \`code\` or code blocks with triple backticks
- **Links**: `[text](url)`
- **Images**: `![alt](image-url)`
- **Headers**: `# H1`, `## H2`, `### H3`
- **Lists**: Use `-` for bullets or numbers for ordered lists

### 🌐 Live Site

View the published blog at: [https://yukishama9.github.io/Helios-Blog/](https://yukishama9.github.io/Helios-Blog/)

### 📖 More Help

For more information about Jekyll and GitHub Pages:
- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Minima Theme](https://github.com/jekyll/minima) (the theme used)

---

Happy writing! 📝✨