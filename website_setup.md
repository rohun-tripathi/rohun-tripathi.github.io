Install hugo 0.134 as

```bash
wget https://github.com/gohugoio/hugo/releases/download/v0.134.0/hugo_extended_0.134.0_darwin-universal.tar.gz
tar -xzf hugo_extended_0.134.0_darwin-universal.tar.gz
sudo mv hugo /usr/local/bin/
```

Make sure the correct hugo is installed
```bash
hugo version
# hugo v0.134.0-77df7bbbff8ce6b56ed693270088de973a87d5ce+extended darwin/arm64 BuildDate=2024-09-03T09:54:22Z VendorInfo=gohugoio
```

Start the server
```bash
cd ~/work/code/rohun-tripathi.github.io
hugo server
```

### Steps to Update Your Website

Your website is configured with **GitHub Actions**, which automatically builds and deploys your site whenever you push changes to your repository.

#### 1. Commit and Push Your Changes
Since your current local branch is `master`, use the following commands to send your updates to GitHub:

```bash
# Add all changes
git add .

# Commit your changes with a descriptive message
git commit -m "Update publications and biography"

# Push to the master branch on GitHub
git push origin master
```

#### 2. Monitor the Deployment
Once you push, GitHub starts a "Workflow" to build your site. You can track its progress:
1. Go to your repository on GitHub: `https://github.com/rohun-tripathi/rohun-tripathi.github.io`
2. Click on the **Actions** tab at the top.
3. You will see a workflow named **"Deploy website to GitHub Pages"** running. 
4. Wait for it to show a green checkmark (usually takes 1–2 minutes).

#### 3. Verify the Update
After the workflow finishes, your changes will be live at:
`https://rohun-tripathi.github.io/`
