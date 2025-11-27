# Basketball Team Manager - GitHub Pages

This directory contains the GitHub Pages site for Basketball Team Manager legal documents and support.

## 🌐 Live Site

Once deployed, the site will be available at:
**https://rohmatmret.github.io/basketball-management-team/**

## 📁 Files

- `index.html` - Homepage with navigation to all documents
- `faq.html` - Frequently Asked Questions
- `terms.html` - Terms of Service
- `privacy.html` - Privacy Policy
- `style.css` - Shared CSS stylesheet
- `_config.yml` - Jekyll configuration for GitHub Pages

## 🚀 Deployment

### Step 1: Enable GitHub Pages

1. Go to your repository on GitHub: https://github.com/rohmatmret/basketball-management-team
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar under "Code and automation")
4. Under **Source**, select:
   - **Branch:** `master`
   - **Folder:** `/docs`
5. Click **Save**
6. Wait 1-2 minutes for GitHub to build your site

### Step 2: Verify Deployment

Visit: https://rohmatmret.github.io/basketball-management-team/

You should see the homepage with links to FAQ, Terms, and Privacy Policy.

## 📝 Updating Content

To update the content:

1. Edit the source markdown files in the root directory:
   - `FAQ.md`
   - `TERMS_OF_SERVICE.md`
   - `PRIVACY_POLICY.md`

2. Run the conversion script to regenerate HTML:
   ```bash
   python3 convert_to_html.py
   ```

3. Commit and push changes:
   ```bash
   git add docs/
   git commit -m "Update legal documents"
   git push origin master
   ```

4. GitHub Pages will automatically rebuild (takes 1-2 minutes)

## 🔗 URLs for Play Store

After deployment, use these URLs in your Play Store listing:

- **Privacy Policy:** https://rohmatmret.github.io/basketball-management-team/privacy.html
- **Terms of Service:** https://rohmatmret.github.io/basketball-management-team/terms.html
- **FAQ:** https://rohmatmret.github.io/basketball-management-team/faq.html

## 📧 Contact

For questions: devrohmat@gmail.com
