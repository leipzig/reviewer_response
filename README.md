# reviewer_response

This generates a slick response summary HTML from a Google sheet used for peer review response triage

Your google sheet must have the following columns
- Identifier [string](e.g. 87LE)
- Reviewer [integer]
- ReviewerImportance [string]
- Request [string]
- Response [string](can contain anchor tags that refer to identifiers for other items e.g. #87LE )

<img width="1717" alt="Screen Shot 2021-06-22 at 1 15 00 PM" src="https://user-images.githubusercontent.com/147991/122985880-ef95f900-d35b-11eb-8bb8-e8d6bbfe0225.png">
<img width="1225" alt="Screen Shot 2021-06-22 at 1 16 47 PM" src="https://user-images.githubusercontent.com/147991/122986049-253ae200-d35c-11eb-89b5-cd2441bffb31.png">
