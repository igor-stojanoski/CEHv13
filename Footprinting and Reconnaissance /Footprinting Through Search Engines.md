### Advanced Google Hacking Techniques
<br>

##### Searches for login pages on specified domain
```shell
intitle:login site:eccouncil.org
```
##### Searches for files related to the search term. In this case PDF files.
```shell
EC-Council filetype:pdf ceh
```
##### Cached version of the web page
```shell
cache:www.eccouncil.org
```
##### Query returns only pages containing the words “EC-Council” and “career” in the URL
```shell
allinurl: EC-Council career
```
##### Query returns only pages in EC-Council site in which the URL has the word “copy”
```shell
inurl: copy site:www.eccouncil.org
```
##### Query returns only pages containing the words “detect” and “malware” in the title
```shell
allintitle: detect malware
```
##### Query returns only pages with anchor text on links to the pages containing the word “Norton” and the page containing the word “Anti-virus”
```shell
Anti-virus inanchor:Norton
```
##### Query returns only pages in which the anchor text on links to the pages contain the words “best,” “cloud,” “service,” and “provider”
```shell
allinanchor: best cloud service provider
```
##### Finds pages that point to EC-Council’s home page
```shell
link:www.eccouncil.org
```
##### Query provides the Google search engine results page with websites similar to eccouncil.org
```shell
related:www.eccouncil.org
```
##### Query provides information about the eccouncil.org home page
```shell
info:eccouncil.org
```
##### Query give you results based around the term EC-Council
```shell
location: EC-Council
```














