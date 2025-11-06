---
layout: default
title: book
permalink: /nlidbs_book/
description: The Never-Ending Quest for Data Accessibility
nav: true
nav_order: 3
---
<div class="post">

    <header class="post-header">
        <h1 class="post-title">NLIDBs with deep learning</h1>
        <p class="post-description">{{ page.description }}</p>
    </header>

    <article>
        <div class="profile float-right">

            {% include figure.html
            path="/assets/img/nlidbs-book.webp"
            class="img-fluid z-depth-1 rounded" -%}
            
            <div class="address">To be released in November 2025.</div>
        </div>


        <div class="clearfix">
            <p>
                This book covers the main research areas that aim to bridge the world of databases and SQL with the world of natural language. It provides a comprehensive coverage of the most influential work in the field that takes advantage of deep learning. Enabling users to access databases using natural language has been a longstanding goal since the inception of relational databases, that despite continued efforts remains an open challenge. However, the advancement of neural networks has given new life to this area, inspiring a new wave of works in multiple directions.
            </p>


            <ul>
                <li>
                    <b>All-in-One Resource</b>: Dives into NLIDBs — from NL, to SQL, to results, and back to NL — in one comprehensive guide
                </li>
                <li>
                    <b>Accessible Yet In-Depth</b>: Tends to all reader levels, with clear explanations and deep insights into the state-of-the-art
                </li>
                <li>
                    <b>Practical and Actionable</b>: Learn how to build NLIDBs with guidance on system integration, challenges, and design choices
                
                </li>
            </ul>


            <p>
                Starting with an introduction on the history of NLIDBs and a brief neural primer on deep learning architectures frequently mentioned throughout the book, the initial chapters focus on the Text-to-SQL problem. There, an overview of the problem is given, followed by a general architecture of Text-to-SQL systems and a deeper analysis of specific systems. Additionally, the reverse process of explaining an SQL query (i.e., SQL-to-Text) is examined, along with open research problems and the currently available solutions. The book continues with the multi-turn Text-to-SQL problem, that enables users to make corrections or ask follow-up questions, outlining the underlying system architectures, and introducing key representative systems. To put everything into perspective the subsequent chapter takes a broader look at the more general areas of code understanding and generation that encapsulate the problems discussed in the previous chapters. Moving on, the focus shifts on generating NL explanations and summaries of data (i.e., the Data-to-Text problem), offering an overview of the problem and its challenges as well as an overall system architecture and specific Data-to-Text systems. Then, bringing Data-to-Text closer to NLIDBs, the book dives deeper into the Results-to-Text problem that focuses on how to express the result of a query in user-friendly natural language. Finally, the book concludes by offering insights into how all the discussed research areas and systems can be brought together to create an NLIDB, along with risk and challenges that must be considered in the process.
            </p>

            <p>
                This book is intended for both researchers and practitioners interested in NLIDBs, regardless of their prior familiarity with the topic. Readers with experience in this area will benefit from a structured overview and categorization of existing systems, along with an in-depth analysis of benchmarks, persistent challenges, and open research questions. Conversely, newcomers can explore the landscape of neural NLIDBs through an accessible presentation of the relevant subfields and key advancements,  without requiring any prior background knowledge. 
            </p>
        </div>
    </article>

</div>