# Quora-Sincere-and-Insincere-Question-Classification


Quora is an American question-and-answer website where questions are asked, answered, and edited by Internet users, either factually or in the form of opinions.

An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle this problem head-on to keep their platform a place where users can feel safe sharing their knowledge with the world.

Quora is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions those founded upon false premises, or that intend to make a statement rather than look for helpful answers.

Here our goal develop models that identify and flag insincere questions. To date, Quora has employed both machine learning and manual review to address this problem. 

An insincere question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is insincere:
- Has a non-neutral tone
  - Has an exaggerated tone to underscore a point about a group of people
  - Is rhetorical and meant to imply a statement about a group of people
- Is disparaging or inflammatory
  - Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
  - Makes disparaging attacks/insults against a specific person or group of people
  - Based on an outlandish premise about a group of people
  - Disparages against a characteristic that is not fixable and not measurable
- Isn't grounded in reality
  - Based on false information, or contains absurd assumptions
- Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers

## Data Description

The Data Set contains 
- the question that was asked
- whether it was identified as insincere (target = 1). 

