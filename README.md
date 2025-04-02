

how to set up locally:

```
cd /Users/tankwin08/Desktop/projects/personal/personal_website
mkdocs serve
```
if you have an error to run at default port 8000, you can run:
``` 
mkdocs serve -a localhost:8001 
```

how to deploy:

Note: If this is your first deployment, you might need to:

1. Go to your GitHub repository settings
2. Navigate to "Pages" section
3. Ensure the source is set to "gh-pages" branch

```
mkdocs gh-deploy
```

After deployment completes, your site should be available at: https://tankwin08.github.io/personal_website