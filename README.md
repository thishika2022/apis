# Multi API Documentation

This repository contains an OpenAPI 3.0 specification that defines three secure API endpoints:

- `/api/housing-living-weightage/` — Fetch housing and socialisation spending totals
- `/api/socialisation-spending/` — Fetch socialisation spending process data (secure)
- `/api/housing-spending-pc/` — Fetch housing spending process chain data (secure)

## 🔐 Authentication

All endpoints require **JWT token authentication**.  
Pass your token in the `Authorization` header:

