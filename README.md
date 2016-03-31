# Euro 2016

Euro 2016 is a web service written in [Node.js][nodejs],
giving you and your friends :boy: :girl: a platform of competition: Who is the
better forecaster of football :soccer: matches? Make bets of future matches,
collect scores and win the crown :crown:.

**Scoring**
- 1 point: correct winner
- 2 points: correct goal difference
- 3 points: correct bet

The [UEFA European Championship 2016][uefa] is taking place in France :fr:
from June 10 to July 10. Happy betting!

## Install
You need to have [PostgreSQL][postgres] :elephant: >= 9.3 installed and
configured with a new database. Node.js is required of course, recommended
versions are >=4.4.0.

    git clone https://github.com/syxolk/euro2016.git
    cd euro2016
    npm install

Now copy `template.config.coffee` to `config.coffee` and set the
database connection.

    cp template.config.coffee config.coffee
    nano config.coffee

## Run
The database structure will be created on first run automatically.

    node index.js

## Credits
Icons made by [Papedesign][papedesign] from [www.flaticon.com][flaticon] is
licensed by [CC 3.0 BY][ccby]

[nodejs]: https://nodejs.org/en/
[uefa]: http://www.uefa.com/uefaeuro/
[postgres]: http://www.postgresql.org/
[papedesign]: http://www.flaticon.com/authors/papedesign
[flaticon]: http://www.flaticon.com
[ccby]: http://creativecommons.org/licenses/by/3.0/