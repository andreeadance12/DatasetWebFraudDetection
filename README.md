# A Comprehensive Dataset for Phishing Detection  

This Git repository hosts a valuable dataset designed for the critical task of phishing website detection. It provides a structured collection of website URLs, labeled to distinguish between legitimate and malicious sites.  

## Dataset Structure  
The core of this repository is a CSV file with the following structure:  

- **nr**: A sequential identifier for each entry (1 to 9048).  
- **url**: The actual URL of the website being analyzed.  
- **verdict**: A binary label indicating the nature of the website:  
  - `0` for legitimate websites.  
  - `1` for phishing websites.  

## Dataset Statistics  
- **Total entries**: 9048  
  - **4928 phishing URLs**: These entries were carefully sourced from well-known and reputable phishing aggregators, ([PhishTank](https://www.phishtank.com/) and [OpenPhish](https://www.openphish.com/)), ensuring a high degree of relevance and accuracy for identifying malicious sites. .  
  - **4120 legitimate URLs**: To provide a balanced perspective, these URLs were drawn from a publicly available [dataset](https://data.mendeley.com/datasets/c2gw7fy2j4/3), ensuring a diverse representation of genuine websites.  

## Supplemental Website Content Files  
A ZIP archive is included, containing individual text files (`1.txt`, `2.txt`, ..., `9048.txt`) with text content of the page for each URL.  

### Use Cases:  
- **Content-based feature extraction**: Analyze text, links, forms, or other webpage elements.  
- **Machine learning models**: Train models using actual webpage content.  
- **Understanding attack vectors**: Examine phishing page characteristics.  

This dataset is ideal for developing different phishing detection solutions.
## The password for the zip file is: phishing
