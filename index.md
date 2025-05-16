---
layout: home
title: "sooyong-liam"
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
