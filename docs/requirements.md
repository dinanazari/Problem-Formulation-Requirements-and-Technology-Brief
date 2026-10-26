# System Requirements

## 1. Functional Requirements
**Image Upload**
The system allow users to upload a news image in JPEG or PNG format.

**Text Input**
The system allow users to enter a news caption or headline.

**Semantic Consistency Analysis**
The system analyse the semantic consistency between the uploaded image and accompanying text using CLIP-based analysis.

**Potential Misinformation-Risk Classification**
The system will classify the submitted image-text pair according to its potential misinformation risk using a defined decision rule.

**Result Presentation**
The system will display the image-text consistency assessment and potential misinformation-risk classification.

**Input Validation**
The system will display an error message when required inputs are missing or invalid.

## 2. Non-Functional Requirements
**Performance**
The system shall return analysis results within 10 seconds for at least 90% of valid submissions under defined test conditions.

**Usability**
At least 80% of participants in a five-user usability test shall successfully submit an image and caption without assistance.

**Security**
The deployed system shall use HTTPS to protect data transmitted between the user and server.

**Reliability**
The system shall display an informative error message for all invalid-input cases in a predefined set of 10 tests.
