# next js

next js is populer open source javascript framework that allows developer to create server-rendered react application with feature like
static site generation , server side rendering , and api routes .
created by vercel, next js is build on top of react and offer advanced feature , tools and optimization that enhance performance , seo and developer productiity

# 1. react based framework:

next js uses react as its core library making it easy for devloper already familier with react to get started , however unlike react which is a client side library , next js provide additional tooling for server side rendering and static generation.

# 2, Rendering modes:

next js support multiple rendering strategy to meet differnet application need :
server side renderiong : renders pages on server for each request, delievering a prerender html page to the client which improve seo and initial load time

static side generation: pre render pages at build time, generating static html file for each pages, this is ideal for pages which dont changes frequently like blog and marketing pages.

client side rendering:
renders content on the client side after the initial page load, ideal for dynamic page with user apecific content.

incremental static regeneration:
allow pages updated after the build process, enabling soime content to be revalidated and updated without a full rebuild, it combine the ssr and ssg

# 3 . file based routing

nextjs simplify the routing with a file based routing approach by creating folders and file within a pages directery.
developer candefine routes easily withput any complex configuration.
for example, afile anmed about.js in the pages folder automatically create a routes /about

# 4. build in api routes:

next js support api routes, allowing developer to build restful api endpoints within the same project, api routes reside within the pages/api directory and can handkle server side function such as form handling , datbase interaction, and more, this is particularly help for simple application that dont need a seperate backend server

# 5. automatic code spliting ans lazy loading

next js optimizes performance by automatic code splitting , this means only the necessary code for the initial load is sent to the client , reducing load time, , additional code is then loaded on demand as the user navigate the site.
this lazy loading strategy help in enhencing performance , espaciallly for large application

# 6.image optimization:

next js provide the build in image optimization, using the next/image component. it dynamically serve images in the optimal formatb and size for each device, reducing page load time and improving perfiormane

# 7. css and styling support:

next js support variou styling option , including css module , sass, and style component, allowing for scoped css and global style,
depending on the need,additionally , it offer built-in support for css in js solution.which work based with component based development.

# 8. enhanced seo:

with feature like server side rendering and static sitegeneration , next js enhance the seo(search engine optimization) , pre rendered content is accessible to searh engine bot.making it more likely to rank higher i search result. it also provide component like next/head for managing meta data and open graph tag., further optimizing seo.

# 9. typescript support:

next js has build in support for typescript , a super set of javascript that adds static typing , this enble developer to write type safe code, improving reliability and catching error early.

# 10. deployment and vercel integration:

next js is designed by vercel , so delpoying next js to vercel is seemless , vercel provide build in ci/cd, serverless fuction, and global edge catching . while simplify the deployment and scaling of next js, while it integrate naturally with vercel , next js can also be deployed on other platform like aws, google cloud, or even traditional server.

# 11. middleware:

middleware in next js allowed you to run code before a equest is completed,this feature is useful for task such as authentication, url rewriting , A/B testing, and more.middleware runs on the server, enabling lightweight manipulation of request withut needing a load of full apiroutes.

# 12. automatic static optimization:

next js automatically determines the best rendering strategy fro each page based on its content, optimizing for either ssr or ssg,
if a page does not want server side rendering, then it will staticaly generate it by default, ensuring optimal performance.

# data fetching option:

next js offer several option for data fetchiing that allow developer to decide the best appriacch for different senario
getstaticprops: for ssg(static site generation),fetching data at build time.
getserversideprops: for ssr(server side rendering),fetching data on each request
getstaticpath:used with getstaticprops, to generate dynamic routes based on external data.
getinitialprops: legacy method to fetch data in both server and client side envoirment.

# developer experience:

next js includes hot reloading, automatic error reporting and a zero configuration setup , allowing developer to focus on writing code rather than focusing on configuring the project.

# edge ready architecture:

the latest version of next js are optimized for edge computing allowing constent and computation occur at the edge of the network rather than a centralized server,
this enable faster response time user around the global.

# use cases:

1. ecommmerse website: (ssr for product page, and ssg for static content)
2. content havey site: lie blog and documentation(ssg fro fast performance)
3. web application with api needs(api routes to handle request)
4. dynamic web app(where content changes frequently, isr for seemless update)

# benifit of next js:

performance: optimize page loading thrtough ssr and ssg
seo: pre rendered pages are better indexed by search engine.
developer experience: minimal configut=raion and robust tooling
scalability: handle a wide varaity of app architecture

next js is power ful framework that enable developer to build highly optimized react application with diverse rendering operation, serverless function, and a smooth development workfow.

# why choose next js:

next js makes it easy to develop and deploy react application with excelent performance , seo benifit, and a streamlined developer experience, by handling server side rendering ,static generation, routing, apiintegration, next js remove the use of external tool and configuration, making it ideal for building scalable and high performance web application.

node js is a framework which is follow many rule and regulation, so every thing in diciplinary manner , so evry thing inside a src (source) directory , inside a src(source) directory there is a app directory , this app directory simply devided into two portion of it, the first part you can easitl called as backend and second part you can easily called as front end and apart from this app not all thing go in app directory something also present outside the appdirectory like models and helper and component file keep outside of the app directory
most of the time you see the backend portion you write inside the api folder, you also use file name as route in api folder, and in frontend part you use file name page also middleware outside the app directory like model helper
