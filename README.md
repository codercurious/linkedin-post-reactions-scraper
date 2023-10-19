# Linkedin post reactions scraper
Interested in using this scraper? Get it here: [Linkedin post reactions scraper](https://apify.com/curious_coder/linkedin-post-reactions-scraper?fpr=ve081&fp_sid=github_linkedin-post-reactions-scraper)
## How it works
Scrape reactions or likes of a linkedin post by providing link to any linkedin post. It gives you name, profile url, reaction type, etc of people who reacted to the post

## Getting Started

Install [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension 

Login to your linkedin account

Click on the extension and export the linkedin cookies

Paste the cookies into this actor's `Linkedin cookie` input field

Here is the sample output of this actor:

```json
{
    "profileId": "ACoAAC4oT_QBnojdo2tLwZGxFBDOoaFi4GvRwTQ",
    "reactionType": "LIKE",
    "name": "Pascal Metivier",
    "headline": "Technicien Leader Section fraisage CN chez Ravaj",
    "profileUrl": "https://www.linkedin.com/in/ACoAAC4oT_QBnojdo2tLwZGxFBDOoaFi4GvRwTQ",
    "connectionType": "3rd+",
    "photoUrl": "https://media.licdn.com/dms/image/C4E03AQEzAnMiq2IzRQ/profile-displayphoto-shrink_100_100/0/1596317924637?e=1696464000&v=beta&t=61DbKTxAXdK232c0qjLTceW9b4n-aDvE9VQ5knLWhdw"
  }
```
