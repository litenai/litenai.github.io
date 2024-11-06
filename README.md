# litenai.github.io
### Static website for LitenAI
#### Directory structure
index.html gets loaded when one visits this site
litenai.github.io
public directory contains the files that get released by firebase
#### firebase release process
It uses Google firebase to deploy the site. The process is as follows:
1. Install firebase tools
```
sudo apt-get install nodejs npm
sudo npm install -g firebase-tools
```
2. Login to firebase
```
    firebase login
    ```
3. Initialize firebase. Needs to be done only once.
   ```
    firebase init
    ```
    Pick Hosting option for Firbase hosting.
4. Copy files to be released in public directory.
5. Check the site locally
   ```
    firebase serve
    ```
6. Deploy the site
   ```
    firebase deploy
    ```

Look at google firebase docs for more details.
