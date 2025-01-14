# <a href="https://colab.research.google.com/drive/1zyrccgZwTn0XQYH9eMH5AzLfCrUXjiu_?usp=sharing" target="_blank">Crawling Data on the Top 10 Most Popular Stocks</a>
<a href="https://colab.research.google.com/drive/1zyrccgZwTn0XQYH9eMH5AzLfCrUXjiu_?usp=sharing" target="_blank">View in Colab by clicking the link</a>

<p style="text-align: justify;">Crawling Data on the Top 10 Most Popular Stocks (as of November 2024) from South Korea's Largest Financial Web Portal <a href="https://finance.naver.com/">Naver Finance</a>.</p>

## **Introduction**
<p style="text-align: justify;">The goal of this project is to retrieve data on key financial indicators for the ten most-searched stocks listed on finance.naver.com.</p>

## **About the Website to be Scraped**
<p style="text-align: justify;">As one of South Korea's largest financial web portals, finance.naver.com provides a wealth of financial and stock market data, serving as a resource for investors and analysts.</p>

## **Project Scope**
<p style="text-align: justify;">This project uses web crawling techniques to retrieve the KOSPI stock codes of the ten most-searched stocks on Naver Finance, along with their corresponding key financial indicators published on the platform. The extracted tables include critical financial metrics such as income, profit, return on investment (ROI), and other essential indicators for assessing corporate performance.</p>

## **Workflow**
<p style="text-align: justify;">The project follows these steps to extract and process financial data:</p>
<ol style="text-align: justify;">
  <li>Utilize the <code>pandas</code> library's <code>read_html()</code> function to scrape data from finance.naver.com.</li>
  <li>Identify and fetch data for the ten most-searched stocks on the platform.</li>
  <li>Retrieve the complete list of KOSPI-listed companies using the <code>StockListing()</code> function from the <code>finance-datareader</code> library.</li>
  <li>Match the stock codes of the ten most-searched companies with the KOSPI-listed companies' table.</li>
  <li>Translate the names of financial indicators from Korean to English.</li>
  <li>Extract the key financial indicators for these 10 companies from finance.naver.com.</li>
</ol>
