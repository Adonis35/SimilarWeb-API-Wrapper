# SimilarWeb API Wrapper

### Authors: Adonis Abdullah
Developed an API wrapper for my former employer, <a href="https://www.oldwellpartners.com/">Old Well Partners</a>, to allow engineers and data scientists to easily access and utilize <a href="https://www.similarweb.com/">SimilarWeb's</a> API. This wrapper would return different website traffic metrics in json format that could then be implemented into different projects.

```python
from similarweb import SMWBAPI

smwb_api = SMWBAPI()

# call a function to gather specific information for a website or app 
# https://docs.api.similarweb.com/
response = smwb_api.get_website_visits(website="google.com")

print(response)
```


#### Responsibilites:
* Developed API Wrapper

#### Technologies:
* Python

#### Outcomes:
* Deployed wrapper internally
* Implemented in company's monthly reporting tools

#### Technology Owner:
* Old Well Partners
