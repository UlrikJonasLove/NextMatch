# NextMatch
Project course "The complete guide to building a full-stack app woth Next.js" with alot of comments for future references

[The complete guide to building a full-stack app woth Next.js](https://www.udemy.com/course/the-complete-guide-to-building-a-full-stack-app-with-nextjs/)

This app is using tailwindCSS and NextUI which is a UI library for React to get nicely looking component designs

### 1. NextJs set up start project + Navbar
* Next.js components are by default server-side
* Needs to explicitly tell next.js to use client when we need client-side functionality
* file-based routing, file needs to be called page.tsx
folderName/page.tsx, in the app folder.
* (folderName)/someName/page.tsx will tell we can href to 'someName'
instead of 'folderName/someName'
#### Hooks
* usePathname() to make link active with custom NavLink component
this hook will give us the current pathname from the url
