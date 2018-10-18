# Framework Validator

The project
Framework Validator is a validator for websites built with frontend frameworks like Foundation or Bootstrap. 

Framework Validator is a part of my next project Frontend Ocean http://frontendocean.com

Links to frameworks descriptions:
Bootstrap 3 
Bootstrap 4 
Foundation 
Semantic UI 

Please take a look and send me proposals of additional frameworks you would like to use.

  
# FDL Language  

To describe available frameworks, I have created a human-like language / compiler.  
The compiler:  
 checks element's static structure and properties/classes  
 checks construction rules  
 checks and adds properties from other (base) elements  
 generates a framework description file  

Example:

Define Header  
as tag h1, h2, h3, h4, h5, h6  
with subheader  

and a general description for one framework element:

Fdl Name base Html-5  
  
Define <ElementName> <OptElementLabel>  
as class1,...  
as tag tag1,...  
as attr attr1=val1,...  
as pos position1,...  
with <"req"> class1,...  
with <"req"> attr attr1=val1,...  
with <"req"> attr attr1 <"number"/...>  
before <element_list>  
after <element_list>  
...  
at <position_list>  
analyze <"body">
  
Come soon for more details.
