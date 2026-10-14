ODUSINA ISAAC PORTFOLIO

This export includes the complete static website and editable source.

WEBSITE
The dist folder contains the ready to host website, including all original images.
Upload the contents of dist to a static hosting provider.

LOCAL PREVIEW
Run this command from the portfolio folder:
python3 -m http.server 8000 --directory dist
Then open http://localhost:8000 in your browser.
Use a web server rather than opening index.html directly because asset paths start at the site root.

EDITING
build.py generates the HTML pages from projects.json and content.json.
Edit dist/style.css for appearance and dist/script.js for interactions.
After editing content, run: python3 build.py
Python 3 is required. No third party Python packages are needed.

DEPLOYMENT
The canonical and social URLs in build.py use the current published site address.
If hosting on another domain, update origin in build.py and regenerate the pages.
The contact form opens a WhatsApp draft for the visitor to review and send.

Hosting credentials, account configuration and Git history are excluded.
