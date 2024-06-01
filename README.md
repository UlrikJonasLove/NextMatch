# NextMatch
Dating app with Next.js


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