# CUIregex
Controlled Unclassified Information (CUI) Regular Expressions (regex) Patterns

The styles defined here are a messed up mix of languages, but they're self-described for searching.

# Assumptions

Assumptions: The following characters are unused by any marking: `

# Styles

## Comments
### Single-line comment
[id] comment
[pattern] \/\/([^\n\r]*)
[example-1]
//  Comment
[example-2]
//  cooey  //
[example-3]
//

### Multi-line comment
[id] multicomment
[pattern] \/\*\*\s*([^*]*)\s*\*\*\/
[example-1]
/** HEADER (optional)
    Indent all
    Leave first and last alone
**/
[example-2]
/**:)**/
[example-3]
/**
**/

## Headers
### Header 1
### Header 2
### Header 3


## Definitions
### id
### patterns
### examples