# Jeystore -> APK Store For Android
[Created by Jeyers Development](https://jd.pnc3.net)

Jeystore is a simple way to access free APKs using a simple client (which is literally a simple HTML file) to download APK files from a GitHub repository, this makes it very easy to add new apps to Jeystore. 
### Jeystore ALWAYS has no ads!

# How do you add your own apps?
## App/Submission Rules:

- Your submission must not modify anybody else's files and it must not add any files outside of your app folder
 - Your app must not contain ANY images, videos, media that are NSFW or not safe for people under 18 (pornography, gore, etc.)
 - Your app must not contain any malware or spyware.
 - Your app must not include any content that infringes copyright, violates DMCA rules, or breaks the terms of any licenses.
 - Your app must not sell/transfer any illegal media.
 - Your app must not attempt to scam or lead people to dangerous websites.
 - LIST IS NOT LIMITING, if we see your app not fitting for Jeystore we will either not accept it or remove it from the store.

To add your own apps create a fork of Jeystore and create a file called 'apps/\<your-apps-title\>/config.json'

**Here is a template:**

    {
      "authors": [
        "Creator1",
        "Creator2",
        "Creator3"
      ],
      "repo_edit_perm": "your_github_username",
      "apk_name": "coolApp",
      "version": "1.0.0",
      "description": "This app is very cool and is a fun tool!",
      "tags": [
        "Tool"
      ]
    }

 **For "apk_name"**
For "apk_name" simply put the name of the apk file you are going to add.
DO NOT add a .apk at the end or it will not be accepted and it won't download.
**Available "tags"**
*Current available tags:*
"Tool", "Game", "Kids", "Vehicles", "Beauty", "Books", "Business", "Comics",
  "Communication", "Education", "Entertainment", "Events", "Finance", "Food/Drink", "Health/Fitness",
  "Lifestyle", "Navigation", "Medical", "Music", "News", "Customization", "Photography", "Other"
  
 ### Add your APK file!
 Add your .apk file in the same directory as the `config.json` file AND with the same name as the "apk_name" in your `config.json` file.
  ### Add your Icon
Add your `icon.png` file in the same directory as before.
  ### Send a Pull Request (use correct format)
Send a Pull Request using the format -> 'Adding \<name-of-app\>'



# How do you edit/update your own apps?
To edit your apps you must fork the repo and use the same account you set as "repo_edit_perm" in the `config.json` file.

### Here are the rules again -> App/Submission Rules :

- Your submission must not modify anybody else's files and it must not add any files outside of your app folder
 - Your app must not contain ANY images, videos, media that are NSFW or not safe for people under 18 (pornography, gore, etc.)
 - Your app must not contain any malware or spyware.
 - Your app must not include any content that infringes copyright, violates DMCA rules, or breaks the terms of any licenses.
 - Your app must not sell/transfer any illegal media.
 - Your app must not attempt to scam or lead people to dangerous websites.
 - LIST IS NOT LIMITING, if we see your app not fitting for Jeystore we will either not accept it or remove it from the store.

  ### Lastly, Send a Pull Request (use correct format)
Send a Pull Request using the format -> 'Edit to \<name-of-app\>'

## AI Declaration
*Artificial Intelligence* aided in creation of the client and the client only.
Remember, Jeystore is not created for a profit, no ads, no selling apps, no fees.
