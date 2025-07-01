# A CLI Tool


## Interactive CLI Demos (DeepGuide Ready!)

This project is pre-configured for [DeepGuide](https://github.com/deepguide/dg) interactive terminal demos.

To add your first demo:
```bash
bunx @deepguide/dg capture
```

Your demo will be auto-validated by CI after you push.


## **Test the Demo CLI**

```bash
# Test Taskly CLI functionality
npm test                    # Shows help
npm run demo               # Runs init demo
./cli.js --help           # Direct CLI usage
```

## **Demo: "Getting Started with Taskly"**


```bash
# Start recording with `dg capture`

# 1. Show help
./cli.js help

# 2. Initialize a workspace  
./cli.js init my-project

# 3. Add some tasks
./cli.js add "Buy groceries" --priority=high
./cli.js add "Write documentation" --priority=medium
./cli.js add "Deploy to production" --priority=low

# 4. List all tasks
./cli.js list

# 5. Complete a task
./cli.js complete 1

# 6. Show completed tasks
./cli.js list --completed

# 7. Show pending tasks
./cli.js list --pending

# Press Ctrl+D to end recording
```
