# CORD19-Machine-Learning
To identify and report all the possible entities related to covid 19 using NLP Named entity recognition in CORD19 dataset.
Pagerank and display relevant articles based on the keywords identified.

Pipeline description:
<ul>
<li>Load all paper metadata</li>
<li>Find papers related to COVID-19</li>
<li>Supervised entity recognition, save as entity text file, format the results to JSON format and render results in HTML format (.json and .html )</li>
<li>Merge all COVID-19 papers' NER results  and extract 10% sample papers' NER results for interactive preview (JSON and HTML).</li>
<li>Simple statistics and barplot of terms occurrences count based on NER results, output TOP occurrence terms from each dict type.</li>
<li>Find related papers by query biomedical topic and keywords (keywords can be empty). Render top paper results in HTML table, highlight the result terms, sorted by count of the irredudant terms.</li>
<li>NER model training based on NER results, write NER model in directory</li>
<li>evaluate NER model prediction results</li>
</ul>

Dataset:
<ul>
  <li>https://www.kaggle.com/mercury825/customized-dict-for-cord19-entity-recognition</li>
  <li>https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge</li>
</ul>  



