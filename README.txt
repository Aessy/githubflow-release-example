Taskr
=====
Taskr is a lightweight task-management API.

Features in this version:
  - User accounts with secure login (JWT, 1h expiry, refresh + logout)
  - Rate-limited login to prevent brute force
  - Task creation, update, delete with ownership enforcement
  - Status lifecycle: open → in_progress → done / cancelled

See auth.txt and tasks.txt for endpoint documentation.

Version: 1.0.0.0
