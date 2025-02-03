# URL-Phishing

My group project is centered around determining the characteristics of invalid and valid URLS by identifying patterns in phishing URLs. These patterns might include validity based on URL length, number dashes, number of dots, and HTTP + SSL. The initial prediction is that invalid URLs (phishing URLs) will be longer, not secure (HTTP instead of HTTPS), and contain significantly more unused special characters such as dots, dashes, and ampersands. One of our team members works at Microsoft as a Software Engineer Intern and a few weeks ago there was a huge Microsoft data breach that stemmed from URL phishing. It compromised hundreds of senior executives' accounts and caused user impersonation, unauthorized data extraction, financial fraud, and much more. I wanted to research this topic since it has a current real world impact on my company and my job. URL Phishing is a major security threat in todays technological world.

Data Set used and variables:

https://www.kaggle.com/datasets/sunnykusawa/phishing-urls

Components of dataset:

'url_length' is the total number of characters in full url

'valid_url' means if the URL is live and able to fetch content from internet

'at_symbol' is the number of times '@' symbol appeared in URL

'sensitive_words_count', - how many times sensitive words appeared in URL. like ['confirm', 'account', 'secure', 'webscr', 'banking', 'login', 'signin'] (we decided not to use this component of our dataset)

'path_length' is the number of characters in path of provided URL

'isHttps' helps to determine if the URL is secured with HTTP + SSL

'nb_dots' is number of time '.' is appeared in URL

'nb_hyphens' is how many time '-' or dash used in URL

'nb_and' is how many times 'and' is used

'nb_or' is the number of times 'or' present in the URL

'nb_www' is how many times 'www' is available in URL string

'nb_com' is the number of time 'com' appeared in URL

'nb_underscore' is how many times '_' used in URL string

'target' is whether given URL is Phishing URL(0) or Non Phish URL(1)
