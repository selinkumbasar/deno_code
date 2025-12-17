Student: Selin Kumbasar
ID: 2021211114

I have implemented 2 features.
I have listed them down under. I have included the video of the implementation with the name "DENO- react video"
1. Caching (Tasks)

First GET /api/tasks loads from fake database

Result stored in in-memory cache

Cache TTL automatically expires

Subsequent requests return CACHE hit

Terminal logs show:

[CACHE] miss → loading from fake DB

[CACHE] hit → returning cached tasks

2. User Accounts & Login / Logout (second work item)

/auth/login backend route accepting email + password

React login page with validation

Successful login switches UI to Task Manager

Logout clears localStorage and returns user to Login screen