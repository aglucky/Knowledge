
## Scraping Stacks
- **Scrapy**
    - Full Framework
    - Support for many tools below
    - Good for big projects
- Requests/Beautiful Soup/Pandas
    - Good for beginners
    - Easy use with Google Colab
    - Speed can be improved via multithreading libraries such as asyncio
- Selenium/Pandas
    - Slowest but also extremely versatile

## Essential Tools
- Developer Tools (I use Edge)
    - XPath Testing
    - Copy API requests as Curl (bash)
        - Convert with Curl to Python website
    - View webpage source files/storage
- Regular Expressions
    - Data extraction when site structure is poor
    - Versatile, but steep learning curve
- XPaths
    - Harder than Beautiful Soup but easier than Regular Expressions
    - Easily tested in devtools
- CSS Selectors
    - More readable than XPaths
    - Not always applicable
- Splash
    - Can be used to render javascript without selenium
    - Great Integration with Scrapy

## Deciding What Stack To Use
```mermaid
graph TD;

1(start)-->q1
q1{Is Site Static?}-- No -->q2{Does Site Use <br> Api for Data?}
q2-- Yes --> e1(Recreate requests in Colab <br>Notebook  and convert responses <br>to pandas datafasme);
q2-- No --> q4{What is the scale <br> of the project?}
q4-- Larger Scale --> e4(Scrapy Project Using <br>Selenium or Splash)
q4-- Smaller Scale --> e5(Selenium Project)
q1-- Yes --> q3{What is the scale <br> of the project?}
q3-- Larger Scale --> e2(Create Scrapy Project)
q3-- Smaller Scale --> e3(Requests and Beautiful Soup <br>in Colab Notebok)

```

## Things to Consider
- How much time will I be spending on this?
- Do I want to risk my IP being blocked (Colab great workaround)
- How much data am I collecting (csv vs Database storage)
- How often will the site be scraped
- Legality/Morality of scrape