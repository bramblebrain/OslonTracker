---
Description: Docker is a platform designed to help developers build, share, and run container applications.
Why: I am learning docker so I can understand how to run self-contained apps that can run on many different systems.
---

```dataview 
LIST without ID
	"**" + this.file.name + "**<br> " + "<progress value='" + (length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100 + "' max='100'></progress>" + "<br>" + round((length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100) + "% completed"
FROM "Goals"
LIMIT 1
```

^lu2jyk

# Tasks
- [x] Installing Docker
- [x] Basic commands
- [ ] Mountpoints [due:: 2024-03-12]
- [ ] YAML
	- [ ] Reusing configuration files
- [ ] Compose
- [ ] Container Management
- [ ] Deployment