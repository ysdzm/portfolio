---
title: PhotoSwipe Test
---

# PhotoSwipe ギャラリー

[![サムネイル](https://pbs.twimg.com/profile_images/1692602187795554304/KOy7bS--_400x400.png)](https://pbs.twimg.com/profile_images/1692602187795554304/KOy7bS--_400x400.png){: data-pswp-width="400" data-pswp-height="400"}

<!-- PhotoSwipe 読み込み -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/photoswipe/5.3.3/photoswipe.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/photoswipe/5.3.3/photoswipe.umd.min.js"></script>
<script>
    document.addEventListener("DOMContentLoaded", function () {
        const gallery = new PhotoSwipe.Lightbox({
            gallery: "body",
            children: "a[data-pswp-width]",
            pswpModule: () => import("https://cdnjs.cloudflare.com/ajax/libs/photoswipe/5.3.3/photoswipe.esm.min.js")
        });
        gallery.init();
    });
</script>
