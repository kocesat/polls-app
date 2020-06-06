POLL APP - MODELS:

Question:
-------------------
- question_text
- pub_date
--------------------

Choice
--------------------
- question: Question as fk
- choice_text
- votes 


Question (fk)-Choice Relations

OneToMany Relations: One question to many choices
if question(fk) is deleted then there is no
reason to keep choices attached to it

[
    MVC patterns- Model -- View -- Controller
    MVT pattern-  Model -- Template-- View
]