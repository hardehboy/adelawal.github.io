---
layout: post
title: Global Findex Financial Inclusion Analysis
description: R Studio Analysis
image: assets/images/pic11.jpg
nav-menu: true
---

Donec eget ex magna. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque venenatis dolor imperdiet dolor mattis sagittis. Praesent rutrum sem diam, vitae egestas enim auctor sit amet. Pellentesque leo mauris, consectetur id ipsum sit amet, fergiat. Pellentesque in mi eu massa lacinia malesuada et a elit. Donec urna ex, lacinia in purus ac, pretium pulvinar mauris. Curabitur sapien risus, commodo eget turpis at, elementum convallis elit. Pellentesque enim turpis, hendrerit.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis dapibus rutrum facilisis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Etiam tristique libero eu nibh porttitor fermentum. Nullam venenatis erat id vehicula viverra. Nunc ultrices eros ut ultricies condimentum. Mauris risus lacus, blandit sit amet venenatis non, bibendum vitae dolor. Nunc lorem mauris, fringilla in aliquam at, euismod in lectus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. In non lorem sit amet elit placerat maximus. Pellentesque aliquam maximus risus, vel sed vehicula.

Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque venenatis dolor imperdiet dolor mattis sagittis. Praesent rutrum sem diam, vitae egestas enim auctor sit amet. Pellentesque leo mauris, consectetur id ipsum sit amet, fersapien risus, commodo eget turpis at, elementum convallis elit. Pellentesque enim turpis, hendrerit tristique lorem ipsum dolor.


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>MyRProject Overview</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      line-height: 1.6;
      background-color: #f9f9f9;
      color: #333;
    }
    h1, h2, h3 {
      color: #2a7ae2;
    }
    ul {
      margin-bottom: 20px;
    }
    a {
      color: #2a7ae2;
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
  </style>
</head>
<body>
  <h1>MyRProject</h1>
  <p>This project analyzes microdata from 2021 to explore financial inclusion trends.</p>
  
  <h2>Task Overview</h2>
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
  <p><strong>“The Global Findex Database 2021: Financial Inclusion, Digital Payments, and Resilience in the Age of COVID-19”</strong></p>
  <p><a href="https://www.worldbank.org/en/publication/globalfindex" target="_blank">https://www.worldbank.org/en/publication/globalfindex</a></p>
  
  <p>The Macro data (country-level) comes from the World Bank Development Indicators</p>
  <p><a href="https://databank.worldbank.org/reports.aspx?source=2&country=ARE" target="_blank">https://databank.worldbank.org/reports.aspx?source=2&country=ARE</a></p>
  
  <h2>Plots</h2>
  
  <h3>Financial Inclusion by Gender and Education Level</h3>
  <img src="barplot.png" alt="Bar Plot: Financial Inclusion by Gender and Education Level" />
  
  <h3>Financial Inclusion vs GDP per Capita</h3>
  <img src="scatterplot.png" alt="Scatter Plot: Financial Inclusion vs GDP per Capita" />
  
  <h2>How to use</h2>
  <p>Open the R project file in RStudio and run the scripts.</p>

  <p>📄 <a href="https://github.com/hardehboy/MyRProject/blob/main/Findex%20R%20Project.R" target="_blank">
    View R script on GitHub
  </a></p>
</body>
</html>
