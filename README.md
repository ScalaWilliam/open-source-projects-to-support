# Open Source projects to support

Here's a list of projects that I use frequently, together with explanations why I think they are worthy of a lot of support (donations & contributions)

- Greenshot: literally the best screenshot software I have ever used. Runs of Windows, and I use it everywhere I use Windows. Easy annotations, amazing and consistent UX. https://getgreenshot.org/
- Jsoup: I use it for two purposes: scraping data and transforming HTML; behaviour and API are very consistent with a great CSS-selector API, and it integrates well with Scala. consistent behaviour with a great CSS-selector API. https://jsoup.org/ - and it's so good I even include it in my Essential SBT tutorial (https://www.scalawilliam.com/essential-sbt/).
- Wireguard: simple and fast VPNs, no complex configurations, just get-it-done approach. And works very intuitively. The best documentation I found is on the Arch Linux website: https://wiki.archlinux.org/index.php/WireGuard
- Puppeteer: gives a very intuitive API to test front-ends with Chromium, including the ability to take screenshots; simple to use with `npm install`. Wish there were a Scala or Scala.js interface :-) Docs https://github.com/puppeteer/puppeteer/blob/main/docs/api.md
- Jetty: the most straightforward Servlet server, with support for streaming as well as embedding.
- Sorttable (Kryogenix): Stuart Langridge's philosophy of not complicating things https://www.kryogenix.org/code/browser/sorttable/ - great talk of his on YouTube - https://www.youtube.com/watch?v=rxlJRydqmk8 "You Really Don't Need All that JavaScript, I Promise"
- Brew: **the** way of installing packages on Mac, eliminating complex install procedures. https://brew.sh/
- Choco: the Brew of Windows. Highly helpful especially when complex dependencies arise (looking at you, node-gyp, who requires Python2 and VC build tools..)  - https://chocolatey.org/
- LibreOffice: extremely fast document processing. I in fact use both Microsoft Office and LibreOffice at the same time. When compatibility and features are concerned, I'm on MS Office, but when I cannot take the performance, I go with LibreOffice, it's just super fast. What is very nice about LibreOffice formats is that they are really plain XML under the surface; I'd done some very interesting work with Scala & LibreOffice. https://www.libreoffice.org/
- Apache POI: can't do without it in the corporate world where Excel and Scala are of significance. https://poi.apache.org/

## Scala
- Scala - the most capable programming language I have used - it is the best you can get in terms of power and also market share. https://github.com/scala/scala
- fs2 - a very well designed library that lets you handle stream processing, integrates with Java reactive streams without problems. https://fs2.io/
- http4s - the best HTTP library (NOT a framework!) I have used. I use it for some production apps together with Jetty, but for some production apps with the Blaze HTTP server. Expressivity is very high and the fact that it is a library makes it highly portable across different environments (think developing your code on a direct HTTP server, and then next moment being able to run it on a corporate Servlet environment). I had written a few extensions to it (https://github.com/scalawilliam/rad4s). At the core of it, it really uses the most appropriate function signature, `Request => IO[Option[Response[IO]]`, which means you can create powerful composed apps, for example to be able to serve different types of routes to different types of users - and reduce the boilerplate, which is impossible to do in many HTTP frameworks. https://http4s.org/
- doobie - 
- cats
- Scala
- shapeless
- Circe
- Scalatags
- Chimney
- scala-native
- SBT
- sbt-native-packager
- Magnolia
- Scalatest
- Scalacheck

