# LinkedIn Company Locations Scraper

**Get the office locations listed on a LinkedIn company page, including address lines and which office is primary. $1 per 1,000 companies.**

Each office is one row. A company is one charge whether it has 2 offices or 45.

## Who is this for?

Enterprise sales and territory planning. Use it when you need every office, not the whole company profile.

## What does a row look like?

```json
{
  "inputUrl": "https://www.linkedin.com/company/example",
  "companyName": "Example",
  "headquarters": "Seattle, Washington",
  "locationCount": 2,
  "address": "Seattle, Washington",
  "addressLine1": "Seattle, Washington",
  "isPrimary": true,
  "success": true
}
```

## FAQ

### Is this a list of every employee by office?

No. These are the offices on the company page.

### Why is this cheaper than Company Details?

Company Details is $2 per 1,000 and returns the website, industry, posts, and offices together. This Actor returns the offices only, at $1 per 1,000.

## Related Actors

Company website and firmographics for headquarters, industry, and website. Company Details for the full page.

## Where to run it

Run the published Actor on Apify, or start from [mawsool.tech](https://mawsool.tech). This repository does not include the lookup address.
