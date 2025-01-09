# biohackathon-finding-dna-eqtls-underlying-a-disease


# Biohackathon Overview

A hackathon is an event, usually hosted by a tech company or organization, where creatives get together for a short period of time to collaborate on a technical project. The participants work [in teams] rapidly and often work without sleep to achieve their task, as the events generally only last 24 hours or take place over a weekend.  Source: https://www.rasmussen.edu/degrees/technology/blog/what-is-a-hackathon/

You have learned a lot about bioinformatics tools in this course and you have skills to perform in silico hypothesis testing.  In this event, you will work with a team and begin to unravel the genetic and biochemical basis of a human disease.   Use any tool you want, but below are prompts that will help guide you on your journey.

Basic rules:  Come to class on both days in Newman or via Zoom. Participate with your team.  Find candidate genes and causal biomarkers. Report your results via github.

# Biohackathon logistics?

The biohackathon will be held on Dec 3 and Dec 5, 2024 from 8am-9.15am.  
Physical Location: Newman Hall 104
Zoom Location: https://clemson.zoom.us/j/9452064261

# Useful Prometheus prompts:

* Prometheus prompts *
```
* What is a complex trait?  What is a Mendelian trait?
* What does it that a complex trait is controlled by a genetic subsystem as opposed to control by a single gene?
* What DNA changes could give rise to aberrant gene expression?  Please compare and contrast the role of changes to RNA production versus changes to protein sequence that could lead to an non wild-type phenotype.
* Why do we call "normal" phenotypes wild-type?
```

# Hackathon Objectives

* Find seed genes underlying a human disease.
* Build a PPI network around the seed genes.
* Find DNA polymorphisms that are associated with altered gene expression.
* Write a report how these candidate genes could be controlling the phenotype.

# Hackathon Tasks
# Task A. Connect with your team. 


# Task B. Select a disease to study.

* Prometheus prompts *
```
* Provide an overview of DISEASE_X from a clinical perspective.  Be specific on symptoms, diagnostic & prognostic criteria.
* What are the frontline treatments for DISEASE_X?  What are the criteria for a successful treatment and what are options if the frontline therapy fails?
* From a physiology perspective, what organs are involved in expression of DISEASE_X?
```

# Task C. Find a gene underlying the disease.

* Prometheus prompts *

```
* From a molecular perspective, what genes are associated with DISEASE_X?
* When are these genes normally expressed in development and in what tissue are they expressed?
* When are these genes abnormally expressed in DISEASE_X and in what tissue are they misexpressed?
* What is the molecular function of the genes that are abnormally expressed that lead to DISEASE_X?
* Please provide 3 hypotheses explaining how the misexpression of these genes leads the DISEASE_X.
```

# Task D. Build a protein:protein interaction (PPI) network using the known gene protein product(s) as seeds.

* Prometheus prompts *

```
* What is the difference between a protein:protein interaction (PPI) network and a gene co-expression network?
* How do I find interacting proteins with a seed protein?  Use the EBI Intact database as an example.  Also note how one can access Intact via Cytoscape.
* How can I visualize and analyze the PPI network?  For example, how can I determine if the network is scale-free? Use Cytoscape as an example tool.
* How can I find pathway and disease enrichment for these genes?  Use Toppfun as an example. 
```

# Task E.  Find tissue-specific eQTLs DNA polymorphisms that could alter the expression of the candidate genes.

* Prometheus prompts *

```
What is an eQTL?  Please explain in the context of the human organism.
How do I find eQTLs associated with genes using the GTEx project?  Please provide an example using breast tissue on eQTLs that control BRCA1 expression.

```
# Task F. Construct an hypothesis that the genes caused the disease phenotype by mechanism X.  

Design an experiment to test the hypothesis that your PPI genetic subsytem network could lead to non wild-type gene expression.

# Task G. Write a report in a github repository and send it to Feltus.

* Prometheus prompts *

```
* How do I create a git repository at github?  How do I add a license and make it public?
* What are the basics of github markdown language?
* Provide a basic overview of the github markdown language.
```

* Github repository products *
 
* Make a git repository and make all teammates members.  
* Write a technical report on your project using the github README file in the github markdown language.
* Include any code in the github repository as a separate file (text file, Jupyter Notebook, etc.)
* Include a Cytoscape file of your PPI network in the github repo.
* Add a plain text file to the github repo listing teammates and what they did in the project.  If someone didn't participate, note that in the file.
* Send the github link to Feltus by December 11 at noon EDT.
