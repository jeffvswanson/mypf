# mypf
Build my own personal finance application.

## Plan
- Build database schema definitions
- Build CLI frontend to perform CRUD on database
- Build frontend web application to interact with backend

### Ideas
- Transactions are splittable
- Transactions have categories
- FIRE calculator
- FIRE progress chart
- Login to get transactions from financial institutions
- Investment account tracking (principal versus gains/losses)
- Investment account rate of return over given time frame


## Architecture
- Database - postgresql
- Code - Go
- Frontend - ???
- Launched with a Docker container
- Kubernetes to manage application and database?

### Ideas
- Try Redis Cache for previous month transactions
- Scale architecture for simulated increased loads, that is, database separated into main and read-only.
