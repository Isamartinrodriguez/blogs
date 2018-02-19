Topics I want to cover below:

* We are not working on issues right now
* We are not ignoring you
* News on v4
  * Internally, it is a complete rewrite
  * Web Components using Stencil
  * Angular layer is thin
  * Relies more on the chosen framework
  * Support for other frameworks is forthcoming
  * For upgrading apps from v3 to v4, there will be breaking changes, but not huge breaking changes
* Ionic v3 should be considered frozen at this point 

What I have currently needs serious refinement (and probably spell checking)...


# Madison, We Have Some Issues...

Many of you have noticed that we have not been keeping a very close eye on the issues lately. Some of you have even let us know that you noticed. This is just a short note to let you know that we are not ignoring you. It may seem like we are, and for that we are truely sorry. We love the Ionic developer community and would never abandon you.

What is actually happening is that the whole team is working towards one major goal: the release of Ionic v4. This is a large effort for our team since this represents a complete refactoring of the Ionic internals. Do not worry, however, as this **does not** mean that your code will need to be completely refactored in order to use v4. Yes, there will be some breaking changes, but most of these are being done in order to clean up the HTML markup.

Here are some facts about Ionic v4:

* All of the components are being re-written as Web Components using Stencil
* The Web Components will be released as `@ionic/core` and will work with more frameworks than just Angular
* Ionic continues to support Angular and will release `@ionic/angular` along with the initial `@ionic/core` release
* `@ionic/angular` is a small set of services and directives that allows effective integration between `@ionic/core` and Angular
* With `@ionic/angular` v4, applications will rely more on modules commonly provided by the Angular framework such as the router, allowing for better integration 
* Integrations libraries will be forthcoming for other frameworks as necessary to support other popular frameworks, in all cases relying as much as possible on the native paradigms of each framework

Because of this, Ionic v3 should be considered "frozen" at version `3.9.2`. There may be a future release at some point due to security fixes. At this time, however, there will not be another "bug-fix" release of Ionic v3. Bug fixing releases will pick up again with version 4 after it is released. We thank you in your patience in this as we move towards releasing version 4.
