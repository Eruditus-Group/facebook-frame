# Facebook Frame

[Facebook Frame](http://sicross.github.com/facebook-frame/) is a self-contained development harness for building and testing [Facebook Applications](https://developers.facebook.com) which work inside Facebook - both in [Canvas](https://developers.facebook.com/docs/guides/canvas/) and in [Page Tabs](https://developers.facebook.com/docs/appsonfacebook/pagetabs/).

Facebook Frame speeds up development by simulating the Facebook iframe environment, including the posting of the `signed_request` parameter. You can configure the contents of the `signed_request`, which makes building, testing and debugging your app really really really simple. Oh, and fast: you can reload your app with new variables in a single click.

Facebook Frame is a single document with no external dependencies, it can be copied and used entirely offline. This means you can keep building your awesome social apps on planes, in tunnels or anywhere the internets do not reach.

Because Facebook Frame is built in Javascript and runs entirely on the client-side, you can be sure that any data you enter - including your app secret - is not passed over the internet to any third party. It's safe for development of your super-stealty app ideas.

Facebook Frame also makes automated testing of your in-Facebook apps a synch. Add Facebook Frame to your project's codebase, and use tools like [Selenium](http://seleniumhq.org/) or [Watir](http://watir.com/) to load your app *as if it was being loaded in Facebook*, and use the config panel to pass in all the combinations of variables that Facebook may pass. This allows your app to be tested as if it were in Facebook, without having to load real Facebook in a browser. You tests will run a little faster because of that.