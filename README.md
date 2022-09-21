## 💾 Specs
- Node v14.x
- MVCS pattern (Model > Route > Controller > Service)
- Classic NodeJS Dependences: Sequelize / Express / Cors / DotENV / HTTPERRORS
- esLint (airbnb config)
- Windows / Unix process platform rules
- Husky / Mocha
- Helpers: Success, Errors & Async Handler
- Github action to prevent "bypass errors"


## 💡 How to:
### Generate new model example:
sequelize model:generate --name User --attributes name:string,surename:string,date:date,mail:string
### Create a new db schema:
sequelize db:create
### Migrate models and asociations:
sequelize db:migrate
### Drop the db schema:
sequelize db:drop 



gabriela
Santiago Quiroz
