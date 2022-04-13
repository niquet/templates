# Design Doc Template
This document is a template for specifying high-level information on implementation strategy
and key design decisions centered on the tradeoffs being considered for a coding project.
It is a relatively informal document that the primary author(s) of a software system or
application create before initiating the coding project. 

The following explains important cosiderations for a design doc, its lifecycle and how to use this
template. If you want to skip to the main content of the template, begin with the
[Context and Scope](#context-and-scope) section.

## Considerations for a Design Doc
- [ ] Are you unsure about the right software design, and would it make sense to spend upfront 
      time to gain certainty?
- [ ] Relatedly, would it help to involve senior engineers, who might not be able to review
      every code-change, in the design?
- [ ] Is the software design ambiguous or even contentious such that achieving organizational
      consensus around it would be valuable?
- [ ] Does my team sometimes forget to consider privacy, security, logging or other cross-cutting
      concerns in the design?
- [ ] Is there a strong need for documents that provide high-level insights into the design of
      legacy systems in the organization?

If you answer yes to 3 or more of these questions, then a design doc is probably a great
method to start your next software project.

## Design Doc Lifecycle

### 1. Creation and Rapid Iteration
Write the doc and share it with colleagues who have the most knowledge about the problem
space. Drive the doc to a first relatively stable version through their clarifying questions
and suggestions. You can use a document editor with a collaboration feature and use it
extensively.

### 2. Review
Share the doc with a wider audience than the original set of authors and close collaborators.


### 3. implementation
### 4. Maintenance and Learning

## Usage of the Template
Each of the following sections is already properly named, along with a brief discussion within
the sections regarding the kind of information you should provide to the target group of your
design doc.

Remember that design documentation is used to express the problems and solutions at a
higher level than code. Make sure that the design decisions that lead to your software
design are relatively easy to comprehend.

Design docs should be just detailed enough to being readable by busy people. Larger projects
can have around 10-20 pages. Split up the problem into more manageable sub problems in case
your design doc is more than that.

For more information on design documents please visit Malte Ubl's posts about
[Design Docs at Google](https://www.industrialempathy.com/posts/design-docs-at-google/)
and [Design docs - A design doc](https://www.industrialempathy.com/posts/design-doc-a-design-doc/).
For a take on Uber's "design docs" visit Gergely Orosz's post about
[Engineering Review Docs](https://blog.pragmaticengineer.com/scaling-engineering-teams-via-writing-things-down-rfcs/).

<br/>
<hr/>

The actual template with the respective sections and their descriptions starts here. <br/> **Have fun
designing software - and writing about it!** 🎉

<hr/>
<br/>

## Context and Scope
This section should be entirely focused on objective background facts and bringing readers
up to speed. Assume previous knowledge and link to detailed info.

**Do** give the reader a very brief overview of the landscape in which the new system is
being built and what is being built.

**Don't** go into heavy details and overexplain every aspect of the project and its
requirements. This is not a reuirements document!

```Think of this section as giving the context or facts about the project.```

## Goals and Non-goals
This section should be entirely focused on listing what goals of the system are and what
aren't.

**Do** provide a short list of bullet points of what the goals of the systems are and what
non-goals are. Non-goals aren't negated goals, but things that could reasonibly be goals,
but are explicitly chosen not to be goals.

**Don't** provide a long and nested list of goals. Additionaly, keep in mind that non-goals
are not negated goals!

```Think of this section as giving the (not so detailed) requirements for the project.```

## The Design
This section should start with an overview of the design and then go into details about it.


### System Context Diagram (Optional)
### APIs (Optional)
### Data Storage (Optional)
### Code and Pseudocode (Optional)
### Degree of Constraint (Recommended)
## Alternatives Considered
## Cross-cutting Concerns
