# Sequelize

[![Build Status](https://travis-ci.org/sequelize/sequelize.svg?branch=v3)](https://travis-ci.org/sequelize/sequelize)
[![Windows Build status](https://ci.appveyor.com/api/projects/status/8xhttm9pxmbmtbwb/branch/v3?svg=true)](https://ci.appveyor.com/project/felixfbecker/sequelize/branch/master)
[![codecov](https://codecov.io/gh/sequelize/sequelize/branch/v3/graph/badge.svg)](https://codecov.io/gh/sequelize/sequelize)
[![Dependency Status](https://david-dm.org/sequelize/sequelize.svg)](https://david-dm.org/sequelize/sequelize)
[![Bountysource](https://www.bountysource.com/badge/team?team_id=955&style=bounties_received)](https://www.bountysource.com/teams/sequelize/issues?utm_source=Sequelize&utm_medium=shield&utm_campaign=bounties_received)
[![Slack Status](http://sequelize-slack.herokuapp.com/badge.svg)](http://sequelize-slack.herokuapp.com)

Sequelize is a promise-based Node.js/io.js ORM for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server. It features solid transaction support, relations, read replication and more.

[Documentation](http://sequelize.readthedocs.org/en/latest/)

## Installation

sequelize 3.35.1 fork版

修改如下：
```
(1842) return 'START TRANSACTION;'; --->  return 'START TRANSACTION';

(1869) return 'COMMIT;'; --->   return 'COMMIT';

(1885) return 'ROLLBACK;'; --->  return 'ROLLBACK';
```

`npm install sequelize-alpha`
