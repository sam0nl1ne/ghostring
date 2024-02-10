# 👻 Ghostring 👻

## [Visit the webring here!](https://ghostring.neocities.org)

## How to Join 
The only required information is your site's **URL** and your desired **slug** (a keyword for your site, e.g. "kersed" for kersed.net).

Optionally, you can also include the following for your site listing: 

- Full **title** of your site
- A brief **description** of your site
- Some form of **contact info** (email, fedi, neocities, etc)
- If you have one, your **RSS** link

Include your information by adding a new entry to *`websites.json`*

### JSON Example

```json
    {
        "name": "Example Website",
        "slug": "example",
        "about": "I'm an example!!! ",
        "url": "https://example.com/",
        "rss": "https://example.com/index.xml"
        "owner": "person@example.com"
    }
```

## Webring HTML

After that, add the webring HTML somewhere on your site, like the sidebar or footer. 
Remember to replace "YOUR_SLUG" with your actual slug: 

```html
<a href="https://ghostring.neocities.org/YOUR_SLUG/previous"><-</a><a href="https://ghostring.neocities.org/">Ghostring</a><a href="https://ghostring.neocities.org/YOUR_SLUG/next">-></a> 
```

It's crucial that every site in the webring has these links (with their slug) accessible on the front page. Otherwise, the ring would be broken, and the site would need to be removed from the list. 
