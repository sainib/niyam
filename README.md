# Niyam : Enterprise Business Rules Management Platform

## It is not your mama's rules engine!

### Description : 
Niyam (means Rule in Hindi language) is a complete platform for Enterprise Business Rules Management Platform. Unlike a language specific rules engine that results in fragment architecture because it cannot scale across programming languages and applications, Niyam works across the enterprise. 


### Requirements & Guiding Principles : 
* Ability to create business rules centrally and apply externally to an application 
* Ability to design, create and apply rules via an easy to use interface
* Ability to support external applications written in different programming languages 
* Avoid making the Rules Servcies as a SPOF (Single Point of Failure) by supporting not only the Rules Services but also support emeddable rules, through a Rules Decriptor File. 
* Platform should also allow developers to extend the functionality by dropping in (plugging in) new operations, assertions so the business rules analysts can use those operations in the rules flow. 
* Platform should provide a pluggable agent into the supported applications. This agent will be a library written in the same programming language as the supported application. The agent will do the following - 
   * Provide interface to call Rules Services from the supported application 
   * Create a callback service for the server to call when there are new rules for this application such that there is a new version of RDF (Rules Description File) is available. 
 
 
### Architecture 
[<img src="https://github.com/sainib/niyam/raw/master/imgs/arch.png">]
