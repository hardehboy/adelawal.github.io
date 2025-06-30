---
layout: post
title: Global Findex Financial Inclusion Analysis
description: R Studio Analysis
image: assets/images/pic11.jpg
nav-menu: true
---

<style>
  body {
    background-color: #ffffff; /* white background */
    color: #2f4f4f; /* dark slate gray main text */
    font-family: Arial, sans-serif;
    max-width: 900px;
    margin: 40px auto;
    padding: 0 20px;
    line-height: 1.6;
  }

  h2, h3 {
    color: #1e3a8a; /* a strong blue for headings */
  }

  p, ul, li {
    color: #2f4f4f; /* same dark slate gray for paragraphs and lists */
  }

  a {
    color: #2563eb; /* brighter blue links */
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  img {
    max-width: 100%;
    height: auto;
    border: 1px solid #ccc;
    margin: 20px 0;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
  }

  /* Optional: style strong/bold text */
  strong {
    color: #1e40af; /* deeper blue */
  }
</style>

<!-- Your HTML content below -->
<h2>Task Overview</h2>
<p>This project analyzes microdata from 2021 to explore financial inclusion trends.</p>
<p>Perform the following tasks in RStudio:</p>
<ul>
  <li>Operationalization and data preparation</li>
  <li>Descriptive statistics
    <ul>
      <li>Bar plot</li>
      <li>Scatter plot</li>
    </ul>
  </li>
  <li>Inferential statistics
    <ul>
      <li>OLS linear regression</li>
    </ul>
  </li>
</ul>

<h2>Data source</h2>
<p>The Micro-Dataset and related resources come from:</p>
<p><strong>The Global Findex Database 2021: Financial Inclusion, Digital Payments, and Resilience in the Age of COVID-19</strong></p>
<p><a href="https://www.worldbank.org/en/publication/globalfindex" target="_blank">https://www.worldbank.org/en/publication/globalfindex</a></p>

<p><strong>The Macro data (country-level) comes from the World Bank Development Indicators</strong></p>
<p><a href="https://databank.worldbank.org/reports.aspx?source=2&country=ARE" target="_blank">https://databank.worldbank.org/reports.aspx?source=2&country=ARE</a></p>

<h2>Plots</h2>

<h3>Financial Inclusion by Gender and Education Level</h3>
<img src="barplot.png" alt="Bar Plot: Financial Inclusion by Gender and Education Level" />

<h3>Financial Inclusion vs GDP per Capita</h3>
<img src="scatterplot.png" alt="Scatter Plot: Financial Inclusion vs GDP per Capita" />

<h2>Results</h2>
<p>Both GDP_PPP and Life_expectancy are highly significant predictors of percent_with_account, with p-values < 2e-16.</p>
<p>The model explains about 43.1% of the v
