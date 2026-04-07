## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.11.1/highlight.min.js"
  integrity="sha384-5xdYoZ0Lt6Jw8GFfRP91J0jaOVUq7DGI1J5wIyNi0D+eHVdfUwHR4gW6kPsw489E"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.11.1/languages/go.min.js"
  integrity="sha384-HdearVH8cyfzwBIQOjL/6dSEmZxQ5rJRezN7spps8E7iu+R6utS8c2ab0AgBNFfH"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-gRTR/fmk+6+ygbihH/fJvHgmffnOrd/eO7DW5zgu1uN9GBohtDx+OBs0DI0ejigB /es/languages/bash.js
sha384-Pg7b9hYE6kefjcNqAabhv8jOLCVoZubUaM4bZFjUJd0CaaQ14ksDI0GVllMtAF4S /es/languages/bash.min.js
sha384-xhohaHGp8S443Qn4JZUYAcKqIIl0bQkFA79EUxpbX8GWb5oufdvvSI9ipl/Dasev /es/languages/c.js
sha384-xaTVEdq02jgKStoYDcZD8NhTN1XV/TWpIu4OM53MtMiLl08+e9YJNENo+R/6Nwp0 /es/languages/c.min.js
sha384-Jrkpn2hK0TY04skYBXB9fj7mMpKYy7g726cPwXGXf6mdBXnFlTDXFduxikMCRXT7 /languages/bash.js
sha384-BbT8tZtvkh8HPXIvL5RtzuljBwI3gR5KIdYxZyYSyI5C/+KNAGdzAiexvmxuroag /languages/bash.min.js
sha384-lAz0Eyld5DmFJB7cxaZonrkUJzGefh+K3niV5d7+vzzS7/P7FEeCJeLNXzMjeo+N /languages/c.js
sha384-tMmX0hBMZeMrZhX6dUNxA94/DNJLl70ao6qu2N9+b/6Ep9Y2e1pBzVjxtLygIB+d /languages/c.min.js
sha384-8v1XxyfOsIlm5lPMtU6/ljyCYUDxHKYksjj+6QTedUdUvdUEgRrWPPgQDS4mdqZt /highlight.js
sha384-l+8L8N8J0pajMjeIr5KUi7UupkKCziY7vm1+O8NmMtnk3VJXx1ghOFqWo3roOUvh /highlight.min.js
```

