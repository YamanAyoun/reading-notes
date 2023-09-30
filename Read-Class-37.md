## What is Jamstack?
The Jamstack has been taking the development community by storm. It offers many benefits that range from performance to cost-effectiveness, all while providing developers with a better suite of tools to work with.

Jamstack is an architectural approach that decouples the web experience layer from data and business logic, improving flexibility, scalability, performance, and maintainability.

Jamstack removes the need for business logic to dictate the web experience.

It enables a composable architecture for the web where custom logic and 3rd party services are consumed through APIs.

## There are great examples of what can make up each part of the stack:

### Javascript
The component that’s probably done the most work to popularize the JAMstack is Javascript. Our favorite browser language allows us to provide all of the dynamic and interactive bits that we might not have if we’re serving plain HTML without it.

### APIs
Utilizing the strengths of APIs is core to how you make a JAMstack app dynamic. Whether it’s authentication or search, your application will use Javascript to make an HTTP request to another provider which will ultimately enhance the experience in one form or another.

### Markup
This is the critical piece. Whether it’s your hand written HTML or the code that compiles down to the HTML, it's the first part you’re serving to the client. This is kind of a de facto piece of any website, but how you serve it is the most important piece.

To be considered a JAMstack app, the HTML needs to be served statically, which basically means not being dynamically rendered from a server.

### One note about "hosting"
Using the term hosting here can be misleading if you’re new to the concept. Yeah, your site is technically getting hosted somewhere, but it’s not in the traditional sense. You don’t have a server that you’re maintaining where you upload your files to with an FTP client like Cyberduck.

Instead, whether your doing it yourself with S3 or piping it into Netlify (which is actually multi-cloud), your HTML and static assets are getting served from object storage. On the tail end of that you typically have a CDN like Cloudflare which caches those files at locations all over the world making your pages load faster for the people visiting your site.

## what makes a JAMstack app so great?


- Speed:
The fact that you’re serving JAMstack apps as static files directly from a CDN (usually) makes it likely your app is going to load super fast. 

- Cost:
More often than not, JAMstack sites are going to run cheaper than their server side counterparts.

- Scalability:
Since you’re serving your files off of static hosting, likely a CDN, that pretty much automatically gives you infinite scalability. 

- Maintenance:
The foundation of your static site isn’t a server, meaning you don't need to maintain it. 

- Security:
Doubling down on the lack of server that you have to personally maintain, you don’t really need to worry as much about locking down ways for people to intrude.


