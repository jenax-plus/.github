## Hi there 👋

This repository contains several lightweight plugins for Apache Jena and its *Fuseki* Semantic Web server.
The individual plugin repositories contain downloads of self-contained Fuseki plugin JARs that can be simply dropped into a Fuseki server's `<fuseki-root>/run/extra` folder such that Fuseki will load them on the next server start. 

* The plugins have minimal non-Jena dependencies. All non-Jena dependencies have been shaded in order to avoid conflicts with other plugins.
* The plugins rely on the public extension APIs of Jena 6+. As long as those APIs don't break the plugins will work against newer versions of Jena.
* The plugins in this *jenax-plus* repository are polished up versions of modules that originated from my Jena-extension project [JenaX](https://github.com/Scaseco/jenax).

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
