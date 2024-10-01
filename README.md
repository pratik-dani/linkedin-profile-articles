# LinkedIn Profile Articles Scraper

This tool allows you to scrape articles from LinkedIn profiles efficiently. Get it here: [LinkedIn Profile Articles Scraper](https://apify.com/pratikdani/linkedin-people-profile-articles). Extract detailed information from Glassdoor job listings efficiently.

## Pricing

For better pricing, you can sign up here: [Datamagnet Pricing](https://datamagnet.co)

## Integrations

Use [Make](https://www.make.com/en/register) to integrate the LinkedIn Profile Articles Scraper with other SaaS platforms, creating custom automation flows.

## Features

- **Data Export and Integration:** Export the extracted data in JSON format. Customize the fields to integrate with other tools and platforms for in-depth analysis.
- **Automatic Retry and Error Handling:** The scraper includes built-in retry functionality to handle network issues or timeouts gracefully, ensuring uninterrupted data collection.
- **Ability to Resume Last Failed Runs:** Resume data collection from the last failed attempt with a simple click, allowing you to pick up where you left off.

## Input Schema

### LinkedIn People Profile Articles

- **url** (string, required): URL of the LinkedIn profile to fetch articles from.  
  _Example_: `https://www.linkedin.com/in/chris-branch-digital-marketing-tips`
- **limit** (integer): Maximum number of articles to fetch.  
  _Default_: 20

## Sample Response

Here is a sample response of the scraper:

```json
[
  {
    "activity_type": "Article",
    "attachments": [
      {
        "image": "https://media-exp1.licdn.com/media/AAYQAgQLAAkAAQAAAAAAAA196XghfnplQFCx7y__C0e55w.png",
        "text": "",
        "type": "Image"
      }
    ],
    "author": {
      "occupation": "I build Personal Brands at Ksa.inhub.ai | LinkedIn Profile Optimization | 🎙 TEDx Speaker + 📘 Educator + ✍️ Author | Former DMD @Prime Ministry / SMM @Zain Jordan | Follow + 🔔",
      "title": "Khaled Elahmad",
      "url": "https://sa.linkedin.com/in/khaledelahmad"
    },
    "comments": "25",
    "created_at": "September 28, 2024",
    "likes": "192",
    "url": "https://ae.linkedin.com/pulse/9-%D8%AD%D9%82%D8%A7%D8%A6%D9%82-%D9%82%D8%A7%D8%B3%D9%8A%D8%A9-%D8%B9%D9%86-%D8%A7%D9%84%D8%AD%D9%8A%D8%A7%D8%A9-%D8%A7%D9%84%D9%85%D9%87%D9%86%D9%8A%D8%A9-%D8%AA%D8%AF%D9%81%D8%B9%D9%83-%D9%84%D9%84%D8%AA%D9%81%D9%83%D9%8A%D8%B1-%D9%81%D9%8A-%D9%85%D8%B3%D8%AA%D9%82%D8%A8%D9%84%D9%83-elahmad-sbm7f"
  },
  {
    "activity_type": "Article",
    "attachments": [
      {
        "image": "https://media-exp1.licdn.com/media/AAYQAgQLAAkAAQAAAAAAAA196XghfnplQFCx7y__C0e55w.png",
        "text": "",
        "type": "Image"
      }
    ],
    "author": {
      "occupation": "I build Personal Brands at Ksa.inhub.ai | LinkedIn Profile Optimization | 🎙 TEDx Speaker + 📘 Educator + ✍️ Author | Former DMD @Prime Ministry / SMM @Zain Jordan | Follow + 🔔",
      "title": "Khaled Elahmad",
      "url": "https://sa.linkedin.com/in/khaledelahmad"
    },
    "comments": "8",
    "created_at": "September 21, 2024",
    "likes": "86",
    "url": "https://ae.linkedin.com/pulse/3-%D8%AE%D8%B7%D9%88%D8%A7%D8%AA-%D9%84%D8%AA%D8%A8%D8%AF%D8%A3-%D9%81%D9%8A-%D8%AA%D9%82%D8%AF%D9%8A%D9%85-%D8%A7%D9%84%D8%AE%D8%AF%D9%85%D8%A7%D8%AA-%D8%B9%D9%84%D9%89-%D9%84%D9%8A%D9%86%D9%83%D8%AF%D8%A5%D9%86-%D9%88%D8%A7%D9%84%D8%AA%D8%B3%D9%88%D9%8A%D9%82-%D9%84%D9%85%D9%87%D8%A7%D8%B1%D8%A7%D8%AA%D9%83-elahmad-fdzqf"
  }
]
```

### Output Data Documentation

Here is the JSON fields documentation without including the sample values:

- **activity_type** (string): The type of activity (e.g., Article).
- **attachments** (array): List of attachments associated with the article.
  - **image** (string): URL of the image.
  - **text** (string): Text associated with the attachment.
  - **type** (string): Type of the attachment (e.g., Image).
- **author** (object): Information about the author.
  - **occupation** (string): The occupation of the author.
  - **title** (string): The title of the author.
  - **url** (string): URL of the author's LinkedIn profile.
- **comments** (string): Number of comments on the article.
- **created_at** (string): Date when the article was created.
- **likes** (string): Number of likes on the article.
- **url** (string): URL of the article.

