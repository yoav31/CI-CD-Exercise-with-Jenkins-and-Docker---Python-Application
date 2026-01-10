
# Jenkins CI Live Demo (v2)
Quick start:
```bash
./demo.sh up
# Open http://localhost:8080 (admin/admin123)
# Trigger the job "Demo-CI-Pipeline" or run ./demo.sh commit "msg" to auto-trigger via Poll SCM
```
Tear down:
```bash
./demo.sh down
```
# Fixed ports to 6000 and enabled push
# Final fix: Registry on 6000, Flask on 5000
