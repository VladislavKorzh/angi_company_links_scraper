## What does Angi (Angie's List) Company Links Scraper do?

Angi (Angie's List) Company Links Scraper let you supercharge your extraction of Angie's List data. By using this unofficial Angie's List Company Links Scraper API you'll get:

- **Location:** State/City/Zip code (Full Address)

- **Category**

- **List of company URLs**

- **List of company URLs together with company name and address**



## Looking for full company details?

Use our [Angi (Angie's List) Scraper](https://apify.com/babak/angi-angie-s-list-scraper) to enjoy the full potential of scraping Angi. Scrape company contact details, general information, and company reviews without limitations in result’s amount.



## How to scrape Angi (Angie's List)

It's easy to scrape Angi with Angi (Angie's List) Company Links Scraper. Just follow these few steps, and you'll get your data in a few minutes.



1.  Click on Try for free.

2.  Enter the search terms or location you want to scrape.

3.  Click on Run.

4.  When Angi (Angie's List) Company Links Scraper has finished, preview or download your data from the Dataset tab.



## Input


| Field Label        | Object Key         | Type     | Description                                                                                                                                                                                                  | Default                    |
|--------------------|--------------------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|
| Location           | location           | string   | Location name as you would search: City name, ZIP code, state.                                                                                                                                               | "Portland"                 |
| Category           | category           | string   | Select a category from                                                                                                                                                                                       | none                       |
| Category page URLs | categoryLinks      | string[] | A list of category URLs, can be added as a file,  remote file or just a list of URLs                                                                                                                         | []                         |
| Zip Codes          | zipcodes           | string[] | A list of US Zip Codes can be added as a file,  remote file or just a list of zip codes                                                                                                                      | []                         |
| Max concurrency    | maxConcurrency     | integer  | Defines how many pages can be processed by the scraper in parallel.  The scraper automatically increases and decreases concurrency based on available system resources. Use this option to set a hard limit. | 100                        |
| proxyConfiguration | proxyConfiguration | object   | Proxy settings of the run. If you have access to Apify proxy, you can set { "useApifyProxy": true" } to enable proxy usage                                                                                   | { "useApifyProxy": false } |



**To start scrapping, please use at least one search field*



## Results

You'll get a dataset containing the output of this actor. The length of the dataset will depend on the amount of results you've set/got. You can download those results as an  _Excel, HTML, XML, JSON,_  and  _CSV_  document or you can just use [Apify API](https://docs.apify.com/api) to get the data.



Here's an example of scraped Angi data you'll get if you decide to scrape all URLs and Addresses of electricians of Los Angeles


```json
[
  {
    "state": "ca",
    "city": "los angeles",
    "category": "electrical",
    "linksArr": [
      "https://www.angi.com/companylist/us/ca/los-angeles/310handyman-reviews-418685.htm",
      "https://www.angi.com/companylist/us/ca/los-angeles/%5Bin%5Dform-builders-reviews-4916185.htm",
      "https://www.angi.com/companylist/us/ca/los-angeles/a-bella-casa-construction-reviews-426034.htm",
      ...
    ],
    "companyDataArr": [
      {
        "link": "https://www.angi.com/companylist/us/ca/los-angeles/310handyman-reviews-418685.htm",
        "name": "310Handyman",
        "fullAddress": "P.O. Box 491282 Los Angeles, California 90049"
      },
      {
        "link": "https://www.angi.com/companylist/us/ca/los-angeles/%5Bin%5Dform-builders-reviews-4916185.htm",
        "name": "[IN]form Builders",
        "fullAddress": "1200 Cliff Dr Los Angeles, California 90065"
      },
      {
        "link": "https://www.angi.com/companylist/us/ca/los-angeles/a-bella-casa-construction-reviews-426034.htm",
        "name": "A Bella Casa Construction",
        "fullAddress": "652 Tularosa Dr Los Angeles, California 90026"
      },
      ...
    ]
  }
]
```


**Object additionalContactInfo, can be unavailable in the future*





## Is it legal to scrape Angi (Angie's List)?

Note that personal data is protected by GDPR in the European Union and by other regulations around the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. We also recommend that you read our blog post: [is web scraping legal?](https://blog.apify.com/is-web-scraping-legal/)
