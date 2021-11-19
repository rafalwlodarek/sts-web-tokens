# sts-web-tokens
Design tokens for web platform<br>
#### Default states and variants
`default` states and variants are ommited in the naming structure to keep the token names short and readable. <br><br>
**Example** <br>
`$button-header-primary-background` *(default state is implicit here and not added to the token name)*<br>
`$button-header-primary-background-hover`  

### main branch
Tokens in the main branch follow component-first naming convention. Component name comes before token category.<br>
`component`-`variant`-`...`-`element`-`category`-`state`<br><br>
**Example**  
`$button-header-primary-text-color-pressed`
### category-first branch
Tokens in the category-first branch follow category-first naming convention. Category name comes before component names.<br>
`category`-`element`-`component`-`variant`-`...`-`state`<br><br>
**Example**  
`$color-text-button-header-primary-pressed`
