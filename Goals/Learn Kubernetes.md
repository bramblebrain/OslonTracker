---
Description: Kubernetes is an open-source container orchestration system for automating software deployment, scaling, and management.
Why: I am learning Kubernetes so that I will have the skills to work on large infrastructure
---

```dataview 
LIST without ID
	"**" + this.file.name + "**<br> " + "<progress value='" + (length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100 + "' max='100'></progress>" + "<br>" + round((length(filter(this.file.tasks.completed, (t) => t = true)) / length(this.file.tasks)) * 100) + "% completed"
FROM "Goals"
LIMIT 1
```

^ezwwcb

# Tasks
- [x] Understanding Kubernetes
	- [x] Try Kubernetes
- [ ] Getting Started
	- [ ] Production environment
	- [ ] Best practices
- [ ] Concepts
	- [x] Overview
	- [ ] Cluster Architecture
	- [ ] Workloads
	- [ ] Storage
	- [ ] Security
	- [ ] Policies
- [ ] Tasks
	- [x] Install Tools
	- [ ] Inject Data into Applications
	- [ ] Run Jobs
	- [ ] Networking
- [ ] Tutorials
	- [x] Hello Minikube
	- [x] Learn Kubernetes Basics
	- [x] Configuration
	- [ ] Security
	- [ ] Stateless Applications
	- [ ] Stateful Applications
	- [ ] Services
