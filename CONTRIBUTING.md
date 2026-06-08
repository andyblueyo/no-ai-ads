# Submission Form
Company:
Category:
Domains:
Reason:

Network rules:
Cosmetic rules (optional):

# Example submission
Company: ExampleAI
Category: Image Generation
Domains:
- example.ai
- app.example.ai

Network:
||example.com^$third-party
##a[href*="example.com"]
##article:has(a[href*="example.com"])

# Guide to how to format properly 
## Example links
! Company Name
||example.ai^$third-party
||app.example.ai^$third-party
||example.com^$third-party

! Perplexity
||perplexity.ai^$third-party

! Cursor
||cursor.com^$third-party

! Runway
||runway.com^$third-party
||runwayml.com^$third-party

## Allowing direct visits
@@||example.ai^$document
@@||claude.ai^$document

## Add cosmetic hiding 
##a[href*="example.ai"]
##article:has(a[href*="example.ai"])
##a[href*="perplexity.ai"]
##article:has(a[href*="perplexity.ai"])
