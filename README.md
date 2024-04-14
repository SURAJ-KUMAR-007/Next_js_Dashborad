## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### styling

> clsx : cases where you may need to conditionally style an element based on state or some other condition.

        useCase:clsx is a library that lets you toggle class names easily.

> Sass which allows you to import .css and .scss files.
> CSS-in-JS libraries such as styled-jsx, styled-components, and emotion.

### Optimizing Fonts and Images

> [Adding a primary font](https://nextjs.org/learn/dashboard-app/optimizing-fonts-images#adding-a-primary-font) >[more about Optimizing Fonts and Images](https://nextjs.org/learn/dashboard-app/optimizing-fonts-images#recommended-reading)

### Routing Fundamentals [link](https://nextjs.org/docs/app/building-your-application/routing)

### Creating Layouts and pages [read](https://nextjs.org/learn/dashboard-app/creating-layouts-and-pages)

> partial rendering :One benefit of using layouts in Next.js is that on navigation, only the page components update while the layout won't re-render.

> Root layout :it is required. Any UI you add to the root layout will be shared across all pages in your application.You can use the root layout to modify your <html> and <body> tags, and add metadata

### Navigating Between Pages

> [Link tag](https://nextjs.org/learn/dashboard-app/navigating-between-pages#the-link-component): we can navigate between the pages without seeing a full refresh. Although parts of your application are rendered on the server, there's no full page refresh,

> Pattern: Showing active links => check the nav-links.tsx file ,their usePathname() hook is used
