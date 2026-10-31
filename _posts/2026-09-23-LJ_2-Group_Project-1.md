---
layout: post
title:  "LJ_2-Group Project-1"
date:   2026-09-23
---

## My Experience

I am happy to share my experience working on our 'Craft of Computing' Group Project-1 . Our team built a tool using a Bash script and Pandoc to convert Markdown files into HTML. The tool automatically handles layouts using header and footer files, copies other assets like images, and has strong error handling for wrong arguments. My main individual feature was writing the logic to take the first heading of a Markdown file and use it as the title of the HTML webpage. I used the head -n 1 command to grab the first line and the # operator to slice off the leading markdown characters, then passed it into Pandoc using --metadata title.Through this project, I learned how to use for loops, if-else conditions, and string manipulation in shell scripting. It was a great learning experience working with my group members, Bagavath and Nithish, as we shared our logic and solved script bugs together. Building this static site generator tool from scratch has given me good practical knowledge and confidence in Linux and automation.