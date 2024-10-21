# SQL Quick Checklist

Here is a quick checklist of SQL best practices:

## 1. Keep Queries Efficient
- Avoid using `SELECT *` in production queries.
- Use indexes on columns frequently used in WHERE clauses.

## 2. Use Proper Joins
- Use `INNER JOIN` for matching data in both tables.
- Use `LEFT JOIN` if you want unmatched rows from the left table.

## 3. Date and Time Best Practices
- Always use `ISO 8601` format (`YYYY-MM-DD`).

```sql
SELECT name, age FROM users WHERE join_date > '2023-01-01';
```

### 3. **Add Styling with GitHub Pages (Optional)**
If you want the blog post to be visually appealing, you can enable **GitHub Pages** and style your post:
- Go to your repository's **Settings**.
- Scroll down to **GitHub Pages** and choose the branch where you want the page to be published.
- You can apply a **Jekyll theme** from GitHub to style your post like a blog.

### 4. **Push Changes to GitHub**
After writing your post, push the changes:
- If you’re using GitHub’s browser interface, commit the changes directly.
- If using **Git** locally, use the following commands:

```bash
git add .
git commit -m "Added SQL checklist post"
git push origin main
```
