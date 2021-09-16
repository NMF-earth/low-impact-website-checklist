# Checklist to build low-impact website

How do we identify a low energy consumption website?

On chrome, do the light house test, performances should be above 90 and in the Network tab, less than 1MB should be transferred. Also, you can expect to have several items of this list :

- no custom font
- no image or few ultra compressed images - even better if they load on demand
- little css/js
- no fancy animations
- no video or compressed video that should only load on demand
- minified css/js
- limited amount of analytics
- few http request to display the page
