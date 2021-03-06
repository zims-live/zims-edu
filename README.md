# ZiMS Edu
[![Discord](https://img.shields.io/discord/808602335671484436?label=Discord&style=plastic)](https://discord.gg/YPJTARyHgD)
[![GitHub CI](https://github.com/neovim/neovim/workflows/CI/badge.svg)](https://github.com/zims-live/zims-edu/actions?query=workflow%3A%22Schedule%22)
## Project Heirarchy
```
|- root
|---- web
|---- core
|---- README.md
|---- CONTRIBUTING.md
```

## Branches
- main - development branch
- release - release branch

## Build and Deployment Servers
- Local Development Server
- Staging Server
- Production Server

<b>Testing in prod is strictly forbidden</b>

## Technology stack
- ReactJS - Frontend
- Node Express - Rest API
- Postgres - Database
- Jest - Testing
- Selenium - GUI Testing Automation (E2E testing)

## Continuous Integration and Continuous Deployment
- Netlify - Static frontend deployment (Migrate to heroku for Server Side Rendering when migrating to NextJS)
- Heroku - Postgres and Node Express REST API deployment

## Contributing
Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidlines.

## License
MIT License
