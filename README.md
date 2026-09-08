# Hey, I'm Anibal

Computer Science graduate working across the stack: Express/TypeScript APIs on the surface, Rust and x64 Assembly underneath. I build self-hosted systems end to end — API, container image, VPS deployment — and measure the parts that matter.

## Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-x86--64-6E4C13?style=flat)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)

## Featured Projects

| Project | What it is | Key mechanism |
| --- | --- | --- |
| [JSONSortFlow](https://github.com/Deadlici0us/JSONSortFlow) | Express/TypeScript API serving deterministic traces for sorting and grid-search algorithms | Factory-selected strategies run on a `worker_threads` pool; sorting returns `steps`/`indexes`, search returns `explored`/`result` |
| [Win64-httpdLite](https://github.com/Deadlici0us/Win64-httpdLite) | HTTP/1.1 static file server in x64 Assembly (MASM) for Windows | IOCP worker loop with per-connection `IO_CONTEXT` from a lock-free SLIST pool and an LRU file cache |
| [Win64-echod](https://github.com/Deadlici0us/Win64-echod) | Asynchronous TCP echo server in x64 Assembly for Windows | IOCP with a worker pool sized at 2x core count; byte-identical round-trip verified by stress tests |
| [BArboleda-backend](https://github.com/Deadlici0us/BArboleda-backend) | Read-only geospatial API over the Buenos Aires tree inventory ([live](https://api.anibal-flores.com/BArboleda/swagger-ui/index.html)) | Spring Boot 3.3 on Java 21; fixed 1000m bucket over a MongoDB `2dsphere` index with a fail-open GZIP Redis cache |
| [Quadtree-Collision](https://github.com/Deadlici0us/Quadtree-Collision) | Boids flocking and elastic-collision physics in the browser ([live demo](https://deadlici0us.github.io/Quadtree-Collision/)) | Rust compiled to WebAssembly; per-frame-rebuilt dynamic QuadTree, up to 9.7x faster than brute force at 10k particles |

## GitHub Stats

[![Anibal's GitHub Stats](/Deadlici0us/Deadlici0us/raw/master/profile/stats.svg)](/Deadlici0us/Deadlici0us/blob/master/profile/stats.svg)

[![Top Langs](/Deadlici0us/Deadlici0us/raw/master/profile/top-langs.svg)](/Deadlici0us/Deadlici0us/blob/master/profile/top-langs.svg)
