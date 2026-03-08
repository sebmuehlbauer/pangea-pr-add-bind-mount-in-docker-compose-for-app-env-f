# Pull Request Submission

## Repository
[acm-udayton/ACM-Meeting-Records](https://github.com/acm-udayton/ACM-Meeting-Records)

## Title
[PR] Add bind mount in docker compose for app/.env file - close #71

## Description
This pull request addresses the requirement to persist environment variables across container restarts by adding a bind mount for the `.env` file within the `docker-compose.yml` file.

### Changes Made:
- Modified `docker-compose.yml` to include a volume mapping for the `./app/.env` file.
- Ensures that environment configurations are correctly passed into the application container.
- Closes issue #71.

## Checklist
- [x] Code follows the project's style guidelines.
- [x] Changes have been verified locally.
- [x] Issue #71 is referenced and will be closed upon merge.

## Submission Status
- Action: Push branch to origin.
- Action: Open Pull Request via GitHub API / Web Interface.
- Status: READY FOR REVIEW