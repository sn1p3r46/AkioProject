# Requirements Engineering Project

<p align="center">
  <img src="RE.png">
</p>
-----


**AUTHORS:**

+ [Andrea Galloni](http://www.andreagalloni.eu) (andrea [dot] galloni [at] studenti [dot] unitn [dot] it )
+ Daniel Bruzual (daniel [dot] bruzualbalzan [at] studenti [dot] unitn [dot] it )

**Organization:** [UniTN](http://www.unitn.it/en)

**Course:** [Requirements Engineering](http://disi.unitn.it/~jm/re/)


-----

## Main Stakeholders:

	1) Tourists
	2) Touristic Operators
	3) Site Administrators
	4) Customer Service
	5) Tourism Boards
	6) Local Business

## Why VOLERE?

	We used VOLERE for requirements specification, to
	identify specific sections:

		1) Purpose of the project (and Goals)
		2) The Client
		3) Mandated Constraints


## Requirements Elicitation Techniques:

	1) Questionnaires (Tourists)
	2) Interview Method (Touristic Operator)
	3) Competitors Analysis
	4) Goal Oriented Analysis


## Goal Oriented Analysis:

	 Early Requirements (System-as-is):

		- Actor Dependency Diagram
		- Goal Diagram

	 Late Requirements (System-to-be):

		- Actor Dependency Diagram (with Akio)
		- Goal Diagram


## Object Oriented Analysis:

	- UML Class-Diagram (leaf nodes of Goal Diagram)


## Why we did not make use of Use-Case Diagrams?

	The Use-Case diagrams are useful to have a clear idea of
	what the stakeholders can do within the system. However,
	we already had a clear picture of this from the goal model
	and from the requirements organized by stakeholder.
	We opted for the class diagram instead, since it gave us
	a better overview of how the different pieces of the system
	connected.


## Requirements Revision and Pre-Validation:

	After the Goal Oriented Analysis we decided to continue
	with requirements pre-Validation based on Goals and then
	we continued with requirements verification.

	The Requirements Revision Matrix is the result of this
	process.


## Requirements Verification and Validation:

	Pre-Validation: as mentioned above we pre-validated
	requirements making use of the goals-to-requirements
	matrix.

	Verification: Analysis performed on every requirement
	we looked for eventual inconsistency, conflicts, remove
	in case of unnecessary requirements and refinining
	rewriting in case of room of improvement.

	Validation: We decided to implement an *Horizontal
	Prototype in order to have a real and reliable feedback
	from customers. To make sure to cover customer's needs.

## Risk Analysis:

	For what concerns the risk analysis we decided to follow
	both the Goal Diagram and Class Diagram paths to spot
	eventual risks and vulnerabilities among procedures and
	while the system is used (or-abused).


## Risk Prioritization:

	For what concerns risk prioritization, the ​Analytic
	Hierarchy Process (​AHP​) have been used. As baseline
	after the risk analysis a score is given to every risk
	based on its ​likelihood and its impact; then a main
	matrix is built, containing all risks attributing a
	preference to every risk pair, defining the precedence.
	All the procedures have been done making use of python
	programming language to ensure reliability,
	reproducibility and precision while managing data.


## Security Requirements

	The elicitation of Security requirements have been
	formalized using (Mis)Use Cases Diagrams, coupled
	with a natural language description in order to get
	completeness and avoid any ambiguity. It is easy to
  understand also from non technical people and
  an affirmed standard. We followed

## Why we did not make use of Abuse Cases Diagrams?

  We did not use those kind of diagrams because there
  are not untrusted external 3rd party actors managing
  sensible data or sensible system procedures.

## Why we did not make use of Secure Tropos?

  Because we had clear who are the legitimate owners of the
  service and who is able to provide the service. We decided
  to provide the minimal needed information to every actors
  to use the properly the service.

## Privacy and Legal Compliance

	To be compliant with the Italian law we performed a
	deep study of privacy and  data collection regulations.

**For more details please have a look to the Assignment3.pdf file of the project.**
