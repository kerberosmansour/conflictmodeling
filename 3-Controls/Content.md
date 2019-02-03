# Managing Potentially Problematic Content

Choices you have include, but are not limited to:

1. Banning certain words/content
2. AI/ML to flag content that meets certain criteria
3. Reporting systems
4. Rate limiting

## Banned word lists
Pros: Simple, predictable

Cons: 
* Real life is not so simple.  See [Zunger17](https://medium.com/@yonatanzunger/asking-the-right-questions-about-ai-7ed2d9820c48) and search for Jay-Z
* You will be accused of censorship.


## Reporting systems
Reporting systems range from Twitter/Facebook-style "flag this content" buttons to DMCA-style reporting.


## Rate limiting
Pros: Stop the spread of fake news.
Cons: Stop activists from organizing the next Arab Spring.  Suddenly popular accounts may be popular for positive reasons.

## Automated Response - AI/ML & Business Logic
With billions of users, and experience with online fraud to back this, on thing that needs to be factored in is automation and buiness logic that balances user experience with threat actor identification. 

###
Most ML challenges can be split in to three parts:

* First, a machine learning problem - what are you trying to predicted, and what is the data that you? 
* Second, cast it as a software problem. What is the API for the problem during production? Who will use the service? How were they doing it today?
* Third as a data problem - What are some key actions to collect, analyze, predict, and react to the data or predictions? Remembering that different input features might require different kinds of actions



### Know your customer
For promoted/paid content there should be an identification/validation (ID&V) process and at the very least before the automation of putting out paid content. The challenge is event a single peice of content can be amplified by casaciding user sharing. 
