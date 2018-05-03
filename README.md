# goblin-bot
## Real-time chat context detection

Detect shitposting, chat topic of discussion, and general attitude or "heat
level" in a chat, in real time. Show status on a webpage. Make data available 
via API. Use GraphQL. Use TensorFlow (perhaps Torch if TensorFlow is too far behind on CUDA versions). **Incorporate an FPGA.**

Abstract the message stream/handler -- allow for "plugins" (backend handlers) to
interop with multiple different chat services.

### Git workflow:
- make a work branch for work (users/githubusername/branchname)
- make changes in that branch
- PR from that branch to master
- delete work branch
- (recommended) after merging and deleting the work branch from within the PR, 
run `git fetch -p` locally to keep a clean local workspace (prunes deleted 
branches)

essentially, one branch per feature/task/"deliverable"
