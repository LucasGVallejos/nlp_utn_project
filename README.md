# Natural Language Processing Project
## Introduction
This repository contains all the practical assignments related to the subject "Natural Language Processing" from UTN FRBA University.

## Sentiment Analysis Practical Work
The diagram presented below provides a high-level overview of the comprehensive process involved in extracting sentiment from various web pages regarding to a specific cryptocurrency:

![Steps](./Sentiment_Analysis/Sentiment_Analysis.png)

<details>
    <summary><b>Define Relevant Tokens</b></summary>
    <p>
    <ul>
    <li>Begin by specifying the tokens related to the cryptocurrency of interest. These tokens will be used to search for relevant web content.</li>
    <li>In this practical assignment I've decided to use "BITCOIN" due its relevant in the market</li>
    </ul>
</details>

<details>
    <summary><b>Retrieve Links from Search Engines</b></summary>
    <p>
    <ul>
    <li>Utilize search engines to conduct searches based on the defined tokens.</li>
    <li>With them I'll retrieve a list of links to web pages that are potentially related to the cryptocurrency.</li>
    <!-- COMPLETE WITH WHICH SEARCH ENGINES I WILL USE AND ADD REF -->
    </ul>
</details>

<details>
    <summary><b>HTTP Requests for Page Retrieval</b></summary>
    <p>
    <ul>
    <li>Initiate HTTP requests to access and retrieve the web pages identified in the previous step.</li>
    <li>This step involves fetching the content from the web for further analysis.</li>
    <!-- COMPLETE HOW I WILL USE THEM AND ADD REF -->
    </ul>
</details>

<details>
    <summary><b>Filter Out Irrelevant Pages</b></summary>
    <p>
    <ul>
    <li>Implement a filtering mechanism to eliminate pages that do not provide valuable information about the cryptocurrency previously defined. </li>
    <li>This ensures that only relevant content is processed.</li>
    <!-- COMPLETE HOW I WILL USE THE FILTERING AND ADD REF -->
    </ul>
</details>

<details>
    <summary><b>Parse HTML Content and Extract Text</b></summary>
    <p>
    <ul>
    <li>Parse HTML content of the web pages to extract meaningful textual information.</li>
    <li>This ensures that only relevant content is processed.</li>
    <!-- COMPLETE HOW I WILL PARSE THEM AND ADD REF -->
    </ul>
</details>

<details>
    <summary><b>Sentiment Analysis</b></summary>
    <p>
    <ul>
    <li>Perform sentiment analysis on the extracted text from each web page.</li>
    <li>Categorize it as positive, negative, or neutral.</li>
    <!-- COMPLETE HOW I WILL USE THE SENTIMENT ANALYSIS AND ADD REF -->
    </ul>
</details>

<details>
    <summary><b>Storage of Sentiment and Pages</b></summary>
    <p>
    <ul>
    <li>Store both the sentiment analysis results and the corresponding web pages in a structured database.</li>
    <li>Categorize it as positive, negative, or neutral.</li>
    <!-- COMPLETE HOW I WILL STORE THEM AND ADD REF -->
    </ul>
</details>
