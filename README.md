# mpvanderschelling.nl redirect

Redirects the discontinued domain `mpvanderschelling.nl` to
[mpvanderschelling.github.io](https://mpvanderschelling.github.io), which is the canonical site.

GitHub Pages serves this repo on the custom domain in `CNAME`. `index.html` and `404.html`
are identical: an instant meta-refresh + JavaScript redirect that keeps the path, with a
`rel=canonical` pointing at github.io. DNS for the domain (TransIP) points at GitHub Pages.

To retire the domain: delete this repo (or its `CNAME`) and remove the DNS records at TransIP.
