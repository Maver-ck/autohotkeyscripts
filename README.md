# autohotkeyscripts
Useful ahk scripts for work

Prerequisites: download ahk from https://www.autohotkey.com/

EnterSofChange.ahk - allows you to auto-populate software package objects from the SOF, C page byt running it and using ctrl-j

STEPS:
1) Edit EnterSofChange.ahk to add the SOF objects you wish to add (this has to be comma separated and on one line)   
2) Run EnterSofChange.ahk
3) Go to the SOF
4) Use option C to go to the source objects page
5) Use ctrl-j to automatically add SOF objects 

SQLParser.ahk - I use this for formatting SQL statements in logs using Sublime (you have to use sublime for this).  This allows you to format SQL in a text editor from a single line to multiple lines, breaking on 
- select
- from
- inner join
- left join 
- where
- union
- group by
- on
- union
- order by
(note it also breaks in "], arguments" as we normally end sql in logs with this. 

STEPS:
1) Copy the SQL from logs 
2) paste it into sublime 
3) run SQLParser.ahk
4) use ctrl-p to format it
