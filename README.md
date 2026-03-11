# Arc Raiders - peon-ping Sound Pack

A [peon-ping](https://github.com/PeonPing/peon-ping) sound pack using audio from Arc Raiders.

## Setup

1. Add your `.mp3` files to the `sounds/` directory:

   | File | Event | Suggested source |
   |------|-------|-----------------|
   | `session-start.mp3` | Session opens | Mission briefing / drop-in audio |
   | `task-acknowledge.mp3` | Tool starts working | "Copy that" / comms ack VO |
   | `task-complete.mp3` | Task succeeds | Objective complete / extraction success |
   | `task-error.mp3` | Task fails | Death sound / mission failed |
   | `input-required.mp3` | Awaiting your input | Comms ping / alert |
   | `resource-limit.mp3` | Rate/token limit hit | Warning alarm |

2. Keep each file under 1MB.

## Publishing

```bash
git init
git add .
git commit -m "initial pack"
git remote add origin https://github.com/sammyfattah/openpeon-arc-raiders
git push -u origin main
git tag v1.0.0
git push origin v1.0.0
```
