# Week 5-6 Exercise Evidence

Name: Mei Morrow
GitHub repository URL: https://github.com/Mei-Morrow/sdi4213-weeks5-6.git

## Part A - Starting validation
- Local pytest result: 15 passed, 1 warning
- Initial CI workflow run URL: https://github.com/Mei-Morrow/sdi4213-weeks5-6/actions/runs/36925893451

## Part B - Week 5 build automation
- Pull request URL: https://github.com/Mei-Morrow/sdi4213-weeks5-6/pull/2
- Successful workflow run URL: https://github.com/Mei-Morrow/sdi4213-weeks5-6/actions/runs/36929017972
- Artifact name: sdi4213-app
- What files are inside the downloaded artifact? app/, requirements.txt, README.md, and VERSION

## Part C - Version and release
- Version: 0.1.0
- Git tag: v0.1.0
- GitHub Release URL: https://github.com/Mei-Morrow/sdi4213-weeks5-6/releases/tag/v0.1.0
- Short release-note summary:

## Part D - Week 6 Docker
- Docker image name and tag: sdi4213-week56:0.1.0
- `docker images` evidence: versioned image exists
- `docker ps` evidence: sdi4213-week56-demo was running with port 8000:8000
- `/health` response: returned status: ok
- `docker logs` evidence: Uvicorn started and GET /health returned 200 OK

Note: Container was stopped and removed but image was confirmed to remain (see screenshots 6-9)

## Reflection
1. What is the difference between a workflow artifact and a Docker image?
2. Why did you tag the Git release and Docker image with a version?
3. What does `-p 8000:8000` do?
4. What would you automate next if this project were moving toward deployment?
