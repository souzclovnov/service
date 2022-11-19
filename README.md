# SERVICE

## Календарынй план

| Этапы                                       | Дата начала | Дата завершения |
|:--------------------------------------------|:-----------:|:---------------:|
| Проектирование и разработка сервиса         | 10.09.2022  |   12.11.2022    |
| Архитектура                                 | 24.09.2022  |   08.10.2022    |
| База данных                                 | 08.10.2022  |   22.11.2022    |
| Функциональный прототип                     | 22.10.2022  |   12.11.2022    |

## База знаний
- [Требования](https://docs.google.com/spreadsheets/d/1ar7k1M1Ny8dvJw3D6-R4sVilpewrDADMEtiyr-7OKU8/edit#gid=0)
- [Архитектурное решение](https://app.diagrams.net/#G1pnGNtSTGczDYFIzFhM41HImrxgo-Cnw7)
- [БД](https://dbdiagram.io/d/635407f44709410195bbe5a8)

## Структура проекта

### src/
```bash
main/
├── kotlin/
│  ├── controller/
│  │  ├── CandidateController
│  │  ├─ EmployeeController
│  │  ├─ PositionController
│  │  ├─ ProjectController
│  │  ├─ SkillController
│  │  └──  VacancyController
│  ├─ model/
│  │  ├─ Candidate
│  │  ├─ Employee
│  │  ├─ Position
│  │  ├─ Project
│  │  ├─ Skill
│  │  └──  Vacancy
│  ├─ repository/
│  │  ├─ CandidateRepository
│  │  ├─ EmployeeRepository
│  │  ├─ PositionRepository
│  │  ├─ ProjectRepository
│  │  ├─ SkillRepository
│  │  └──  VacancyRepository
│  ├─ service/
│  │  ├─ CandidateService
│  │  ├─ EmployeeService
│  │  ├─ PositionService
│  │  ├─ ProjectService
│  │  ├─ SkillService
│  │  └──  VacancyService
│  └──  HrApplication
└── resources/
   ├─ static/
   ├─ templates/
   ├─ aaplication.yml
   └──  data.sql
```
## Начало работы

Клонировать репозиторий:
git
git clone https://github.com/souzclovnov/service.git

Проект запускается локально
