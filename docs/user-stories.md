# User Stories
## User Story 1: Image and Caption Submission
**Related Requirements:** FR1, FR2, FR6
As a news reader, I want to upload a news image and enter its accompanying caption so that I can assess whether they are semantically consistent.

### Criteria
1. The system accepts images in JPEG and PNG formats.
2. The user can enter a news caption or headline.
3. The system displays an error message when an image or caption is missing.
4. The system accepts valid image-text inputs for further analysis.

## User Story 2: Semantic Consistency Analysis
**Related Requirements:** FR3, FR4
As a news reader, I want the system to analyse the semantic relationship between an image and its caption so that I can identify potential inconsistencies that may indicate out-of-context misinformation.

### Criteria
1. The system processes valid image-text inputs using CLIP-based analysis.
2. The system generates a semantic consistency score.
3. The system applies a defined decision rule to assess potential misinformation risk.
4. The system produces a potential misinformation-risk classification.

## User Story 3: Analysis Result Presentation
**Related Requirement:** FR5
As a news reader, I want to view the image-text consistency assessment so that I can make a more informed decision about the news content.

### Criteria
1. The system displays the image-text consistency assessment.
2. The system displays the potential misinformation-risk classification.
3. The system presents the results in a clear and understandable format.
4. The system informs users that the assessment does not independently verify the factual accuracy of the news.
