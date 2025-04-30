# AI Action Plan Comment Analysis

This project is an NLP analysis of the [AI Action Plan comments](https://www.nitrd.gov/coordination-areas/ai/90-fr-9088-responses/) submitted to and collected by NITRD.

## Notes

- These comments are not currently available on Regulations.gov, which limits the amount of metadata I can access for each submission.
- Regulations.gov typically provides rich metadata such as:
  - Date submitted  
  - Author(s)  
  - Page count  
  - Location information  
  - Organization name  
- In contrast, NITRD only provides a ZIP file containing the comments as PDFs, with no accompanying metadata.

### Planned Approach

- **Initial Metadata Extraction**:  
  I will begin by extracting the file name and page count from each PDF.

- **Text Scraping & Enrichment**:  
  Once text is extracted from the PDFs, I’ll identify:
  - Submission date  
  - Organization name  
  - Other relevant details

- **Categorization by Submission Type**:  
  NITRD provides high-level submission type categories on their [website](https://www.nitrd.gov/coordination-areas/ai/90-fr-9088-responses/). I plan to incorporate these into my analysis as an additional metadata layer.


This extraction will be difficult to do. I have reached out to NITRD to see if they are willing to provide this information.