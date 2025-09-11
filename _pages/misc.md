---
permalink: /misc/
title: "Hobbies"
author_profile: true
redirect_from:
  - /misc.html
---
## Running
I have completed three half-marathons (2:21:32), and also numerous 5K (28:28) and 10K (1:02:12) races.

I am active on Strava. Follow me [here](https://www.strava.com/athletes/43863750).

## Photography

<p>
  See the full gallery on
  <a href="https://unsplash.com/@YOUR_UNSPLASH_USERNAME?utm_source=abhinavgor_portfolio&utm_medium=referral" target="_blank" rel="noopener">Unsplash</a>.
</p>

<div id="unsplash-gallery" class="unsplash-grid"></div>

<style>
  /* simple responsive masonry-ish grid */
  .unsplash-grid {
    column-width: 300px;
    column-gap: 1rem;
  }
  .unsplash-item {
    break-inside: avoid;
    margin: 0 0 1rem;
  }
  .unsplash-item img {
    width: 100%;
    height: auto;
    display: block;
    border-radius: 8px;
  }
  .unsplash-caption {
    font-size: 0.85rem;
    margin-top: 0.35rem;
    opacity: 0.8;
  }
</style>

<script>
  (async function () {
    const USERNAME = "YOUR_UNSPLASH_USERNAME";
    const PROXY = "YOUR_PROXY_URL"; // e.g. https://unsplash-proxy.yourdomain.workers.dev
    const perPage = 30;

    const url = `${PROXY}/users/${encodeURIComponent(USERNAME)}/photos?per_page=${perPage}&order_by=latest`;

    try {
      const res = await fetch(url);
      if (!res.ok) throw new Error("Unsplash proxy error: " + res.status);
      const photos = await res.json();

      const container = document.getElementById("unsplash-gallery");
      container.innerHTML = photos.map(p => {
        const photoLink = `${p.links.html}?utm_source=abhinavgor_portfolio&utm_medium=referral`;
        const userLink  = `${p.user.links.html}?utm_source=abhinavgor_portfolio&utm_medium=referral`;
        const alt       = p.alt_description || p.description || "Unsplash photo";

        return `
          <figure class="unsplash-item">
            <a href="${photoLink}" target="_blank" rel="noopener">
              <img src="${p.urls.regular}" alt="${alt}">
            </a>
            <figcaption class="unsplash-caption">
              Photo by <a href="${userLink}" target="_blank" rel="noopener">${p.user.name}</a> on
              <a href="https://unsplash.com/?utm_source=abhinavgor_portfolio&utm_medium=referral" target="_blank" rel="noopener">Unsplash</a>
            </figcaption>
          </figure>
        `;
      }).join("");
    } catch (err) {
      console.error(err);
      document.getElementById("unsplash-gallery").textContent =
        "Sorry—couldn’t load photos right now.";
    }
  })();
</script>