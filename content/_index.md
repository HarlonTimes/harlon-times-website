---
hero:
  heading: Harlon Times, Harlon's major news outlet.
  maxWidthPX: 652
seo:
  image: /images/hero-2.jpg
---
<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
<script>
  if (window.netlifyIdentity) {
    window.netlifyIdentity.on("init", user => {
      if (!user) {
        window.netlifyIdentity.on("login", () => {
          document.location.href = "/admin/";
        });
      }
    });
  }
</script>