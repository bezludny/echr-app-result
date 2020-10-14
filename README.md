# echr-app-result
European Court of Human Rights - State of Proceedings Online parser

This is a command-line parser to get info from http://app.echr.coe.int/SOP/ by application number


## Usage
```
ruby check.rb APPLICATION_NO
```

Example response:
```
Collecting required params...
Querying...
INFO
------
NO: XXXXX/YY
DATE: 06/08/2008
TITLE: Lorem ipsum dolor sit ame
REP NAME: Excepteur sint occaecat
CURRENT STATE: Application finished
LAST MAJOR EVENT: 16/02/2020

EVENTS
------
[16/02/2020] Judgment on merits and just satisfaction final: case is finished
[16/01/2020] Judgment on merits and just satisfaction
[20/02/2013] Communicated to the Government for observations
[12/05/2009] Application requiring a decision

```
