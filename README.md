# P001_LinkedIn_DWDM
Analysis of terms in Linkedin Job Descriptions related to DWDM

## Description
Scrapped LinkedIn webiste (public without login in) for job search worldwide that include the term DWDM.  Extract job descriptions and look for other common terms included in these job offers.

#### Steps
* Web scrapped LinkedIn using Selenium library and saved results in .csv file
* Clean and tokenized job descriptions
* Compared list of tokens with a list of technical terms extracted from Techopedia.com
* Obtained most common terms and visualized using WordCloud

### Core Libraries
* Selenium
* NLTK
* WordCloud
* Pandas
* Matplot
* Collections

### Sources
* https://maoviola.medium.com/a-complete-guide-to-web-scraping-linkedin-job-postings-ad290fcaa97f
* Garrett, John. Data Analytics for IT Networks (Networking Technology). Pearson Education. Edición de Kindle.
* https://www.techopedia.com/dictionary 
* https://stackoverflow.com

### Result
![alt text](https://github.com/telecomds/P001_Linkedin_DWDM/blob/main/word_cloud_img.png?raw=true)

### Future work
* Use Linkedin login to scrap
* Unify data language.  Actual data include mix of english and spanish terms
* Graph/analyze rest of data scrap (now just showing counts)



