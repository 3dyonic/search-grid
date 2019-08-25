# Search Grid Example 
assignment by Yonatan Lev Ari

## Specification
1. build responsive page according to design. 

## Development dependencies:
simple npm configuration with node sass


### Highlights
A design system focused solution.  
component based.  

#### Expected beheviour: 
1. responsive.
1. can be maintained on a large scale.
1. pixel perfect

## Styling methods: 
- scss with sass-lint configuration
- role based architecture
  - seperation between global and component scope.
  - configuration based for global and component scope.
  - style guide as a global definition layer
- BEM ,OOCSS.
- Component selectors are self containted and isolated.  
  - using global tokens for configuration
  - using global mixins and functions
- Utilized mixins and functions for selector indipendent future re-use.
- Rule based linting


### Issues with Design: 
- no style guide, i had to interpet from design, hard to invent semantics and relationships.
- for this reason i have very few utils and atomic related classes, 
  - this can be amended quickly when we need because function and token based approach for configuring my components.
  - used based unit of 10pixels, floored and cieled fy units of 5pixels when needed, for consistency,
- provided design was not component based. 
  - provided desing was delivered with max resoution, much harder to interept for mobile. 
  - i created mobile solution, as i understood from design logic.
  - side bar menu added.
- no icons and fonts provided
  - i imporvised, the hacked font i used have some line height issues. (i hacked it, but it is controlled by a flag and a mixin and can easily be turned off),
  - used some referanced fonts.
  - used referance logo.

### not deliverd: 
- range selector (in real life the is an external component)
- drop down select (in real life the is an external component)

### PIXEL PERFECT defect: 
- card content is not identical because assets where missing. 


### Notes:
total work is circa 9 hours.