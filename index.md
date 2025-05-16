---
layout: home

# this block must start at line 1 with exactly three hyphens, no leading spaces!

hero:
  title: "Dive into our curated math content"
  # you can omit `image:` if you just want a solid background color
  image: "/assets/images/math-hero.jpg"

sections:
  - title: "Courses"
    description: "Self-paced modules"
    url: /courses/       # ← Note: use `url:`, not `link:`
    icon: book
  - title: "Blog"
    description: "Deep dives & updates"
    url: /blog/          # ← again, `url:` here
    icon: pencil-alt
  - title: "Exercises"
    description: "Practice problems"
    url: /exercises/
    icon: puzzle-piece
---

If you still see this text instead of cards, check:

1. **Front-matter delimiters**  
   - Must be `---` on lines 1 and the closing `---` immediately after your YAML.  
   - No extra spaces or tabs before those `---`.

2. **Key names**  
   - `layout: home` → must use exactly “home” (lowercase).  
   - In each section, the link property is `url:`, *not* `link:`.

3. **File location & name**  
   - This file must be exactly `index.md` (or `.markdown`) in your repo root.  
   - GitHub Pages must be set to build Jekyll from that branch.

4. **Build errors**  
   - Check your repo’s GitHub Actions / Pages build log for YAML parse errors.

Once your `index.md` looks like the snippet above, push it up and within a minute you should get the full hero + three card layout. Let me know if it’s still stubborn!
