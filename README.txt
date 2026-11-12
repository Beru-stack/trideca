Trideca — DBT 1305 Week 7 Team Project example
================================================
A complete, valid example that follows the Week 7 assignment:

Pages (6): index, about, products, orders, register, contact
Stylesheet: css/style.css — ONE file, linked from every page
House style (top of style.css): main #0b6b4f, ground #f6f1e7, ink #1f2937, accent #f59e0b
  Headings: Georgia, serif — Body: Arial, sans-serif
Layout: body is a Grid with named areas (header/nav/main/aside/footer)
  Nav is a Flexbox row; cards are a Flexbox row that wraps
Phone: viewport tag on every page; one media query LAST in style.css,
  max-width 700px, single column, no sideways scroll from 360px up
No inline styles, no <style> blocks.

HOW TO USE IN VS CODE
1. Open VS Code > File > Open Folder > choose the trideca-team-project folder
2. Open index.html, right-click > Open with Live Server (or open the file in a browser)
3. Change the colours / text to your own team project, keeping the same structure
4. Each member: git pull before you start, git add/commit/push after, with a sentence message

TO UPLOAD TO GITHUB
1. Create a new repository on GitHub (do NOT tick "Add a README")
2. In VS Code terminal, in this folder:
   git init
   git add .
   git commit -m "First version of Trideca team site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/trideca.git
   git push -u origin main
3. On Google Classroom, under Team project — repository, share ONLY that repository URL.
