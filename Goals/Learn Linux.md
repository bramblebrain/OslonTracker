---
Description: Linux is a family of open-source Unix-like operating systems based on the Linux kernel
Why: I am learning Linux because it is the most popular server operating system and can open many opportunites.
---

```dataview 
LIST without ID
	"**" + this.file.name + "**<br> " + "<progress value='" + (length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100 + "' max='100'></progress>" + "<br>" + round((length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100) + "% completed"
FROM "Goals"
LIMIT 1
```

^mw6rov

# Tasks
- [ ] Introduction to Linux and shells
- [ ] Using `man`
- [ ] Navigating the filesystem
- [ ] Permissions
- [ ] Piping
- [ ] Scripting
- [ ] Scheduling tasks
- [ ] Finding things
- [ ] Finding things in things


