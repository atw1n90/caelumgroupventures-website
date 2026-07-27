# Favicons

Drop these next to index.html and add to <head>:

    <link rel="icon" href="favicon.svg" type="image/svg+xml">
    <link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon-16.png">
    <link rel="apple-touch-icon" href="apple-touch-icon.png">

(index.html already references favicon.svg — the PNGs are fallbacks for older
browsers and iOS home-screen icons. 16/32 use the simplified no-lines mark for legibility.)
