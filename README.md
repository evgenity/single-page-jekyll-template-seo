# Single page jekyll template with SEO

I use this template to test my crazy startup ideas.

The methodology behind this is "don't wait, publish a landing page with description and see".

# Deployment strategy
- [ ] Find a crazy idea
- [ ] Register crasy-idea.com at https://namecheap.com
- [ ] Clone this repo `git clone https://github.com/evgenity/single-page-jekyll-template-seo crazy-idea` or fork it
- [ ] edit `_config.yml` where needed
- [ ] install jekyll by `gem install jekyll`
- [ ] `jekyll build`, your site will be built at `_site` folder
- [ ] publish your web site contents online: I prefer nginx self-hosting at https://www.digitalocean.com
- [ ] get SSL certificate at https://letsencrypt.org
- [ ] configure https/http2 at nginx with https://mozilla.github.io/server-side-tls/ssl-config-generator/
- [ ] check you got A+ at https://www.ssllabs.com/ssltest/
- [ ] check your SEO at http://seositecheckup.com
- [ ] submit your site for indexing on https://www.google.com/webmasters/tools/ and more
- [ ] add google analytics https://analytics.google.com
- [ ] start developing an MVP for your crazy idea; meanwhile google will index your keywords - check google analytics dashboard

# Publishing site
- [ ] To learn how to setup a convientient git deployment see: https://www.digitalocean.com/community/tutorials/how-to-set-up-automatic-deployment-with-git-with-a-vps

# To fork your own repo 
1. create a new repo
2. clone it on your computer
3. add the original repos as upstream source; `git remote add upstream [url]
4. fetch and merge upstream: git fetch upstream & git merge upstream/master
