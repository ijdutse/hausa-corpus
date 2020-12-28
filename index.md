## HauBERT -- a pretrained collection of Hausa corpus

Despite the large number of people speaking the language, Hausa is categorised as a low resource language when it comes to NLP-related tasks. Thus, the aim of this project is to enrich the the language with useful tools that will facilitate downstream tasks in the language. While there exist useful resoruces in this respect, they are mostly centered around formal text collections notably from news sites, such as BBC Hausa, VOA Hausa, etc, to enrich the language for NLP-related tasks. This project observes the need to expand and to include other sources with informal collections mostly from social media platforms. As such, we offer contributions in this respect and describe the cuation process -- from collection to training of a lnaguage model suited for the language.

You can use the [editor on GitHub](https://github.com/ijdutse/hausa-corpus/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

#### Introduction
Hausa language belongs to the Afroasiatic language phyllum, one of the most spoken Chadic language. It is estimated that over 80 million people speak the language mostly in Western Africa nations. Despite this popularity, there are limited resources to fully utilise in automatic speech recogntions (ASR) and other NLP automated tasks. Despite the enourmous access to tones of data, Googles translation API performs poorly/sruggle to make sense of spoken/speech in the language. With the growing utility of such approaches and the evolving nature of communcation in which majority of the populace obtain useful information from the web and social media platforms, it is pertinent to streamline the process/tools/resources to harness in enriching the language with the relevan resources. This study contributes a rich collection of formal and informal forms of the language from refutable websites and social media groups, respectively. This is the first comprehensive collection of the corpus.


### Curation Process

###### Category I: Web Scrapping 
- using BeutifulSoup package to scrap useful data from relevan websites that provide information in Hausa language 
***News Channels*** (from respective websites and corresponding social media handles): this collection mostly consists of well-written text (abidng by formal writing style) to post or break news on social media platforms such as Twitter. Naturaly the post attracts other users to engage -- comment, retweet/share and like -- which allows for retrieving of relevant users and how they engage in the local language using slangs, memes and other colloqual or informal posting style. This category forms the first generation.The focus is on the following sites: 
  - BBC Hausa: https://www.bbc.com/hausa
  - Voice of America (Muryar Amurka): https://www.voahausa.com/
  - Freedom Radio Kano (Muryar Jama'a): https://freedomradionig.com/
  - Hausa Newspapers:
    - Triumph ... need to request it from LCC library - see details https://www.loc.gov/rr/pdf/requestingmaterials.pdf
    - Leadership Hausa
    - Daily Trust -Blog Posts: http://indigenousblogs.com/ha/
  - Other resoyrces: 

Because those websites used the formal version of the language, it will be useful in studying the formal written form of the language.


###### Category II: Social Media Posts via APIs: 
***Social media posts*** (from users engaging with the online posts on various social media platforms): this category consist of diverse users that interacts with the post from News Channel. The users' content and their relevant networks are used to collect further data for the analysis. Social media platforms of interest include: 
- TWITTER:
    - Usernames-based data collection: this is based on using specific usernames to collect relevant data for analysis .
- FACEBOOK: 
- INSTAGRAM: 
-  .... 


to be continued .... 

###### A basic translation process of the collected corpus
We leverage Google Translation Engine to translate the collected datasets. Each segment/sentence in the collection is translated using Googletrans and validated by human users to assess the efficacy of the process.


```markdown
Syntax highlighted code block

# Hausa Corpus
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ijdutse/hausa-corpus/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
