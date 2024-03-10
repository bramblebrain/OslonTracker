---
Description: Hugo is an open-source static site generator that is fast and flexible.
Why: I am learning Hugo so I have a place to share my blog posts.
---

```dataview 
LIST without ID
	"**" + this.file.name + "**<br> " + "<progress value='" + (length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100 + "' max='100'></progress>" + "<br>" + round((length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100) + "% completed"
FROM "Goals"
LIMIT 1
```

^z7li9t

# Tasks
- [x] Installation
- [x] Content management
	- [ ] Templates
- [x] Functions
- [x] Methods
- [ ] Render hooks
- [ ] Hugo modules
- [ ] Hugo pipes
- [x] CLI
- [x] Hosting and Deployment