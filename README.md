The-non-developers-guide-to-web-related-buzzwords
=================================================

###The No-Nonsense, Completely Authoritative, Non-Developer’s Glossary To Web and Web-related Buzzwords


####Contents
1.  [Above the Fold](#above_the_fold)
1.  [Adaptive Design](#adaptive_design)
1.  [Content First](#content-first)
1.  [Context Aware Responsive Experience (CARE)](#context_aware_responsive_experience)
1.  [Context Buckets](#context_buckets)
1.  [Device Buckets](#device_buckets)
1.  [Device Detection](#device_detection)
1.  [Feature Detection](#feature_detection)
1.  [Fluid Grids](#fluid_grids)
1.  [Graceful Degradation](#graceful_degridation)
1.  [HTML5](#html5)
1.  [Liquid Layouts](#liquid_layouts)
1.  [Mobile First](#mobile_first)
1.  [One Web](#one_web)
1.  [Progressive Enhancement](#progressive_enhancement)
1.  [Responsive Design](#responsive_design)
1.  [Responsive Experience](#responsive_experience)

#####[Above the Fold:](!above_the_fold)
A metaphor borrowed from printed newspapers where the most important or engaging content was placed on the front page on the top half, so as to be immediately visible to passers by when folded and on display.

The term came to be applied to web pages to mean content that is displayed to the visitor without the need to scroll. This carried a great deal more weight and meaning when there were a narrow number of screen sizes available to visitors of websites, but carries very little meaning today due to the shear number of screen sizes at which a web page can be accessed.

“The Fold” was a term used to describe a specific need (attention) in specific medium (newspapers) in a very specific context (passing by a newsstand). While there are very similar needs for web sites, the media and contexts are greatly different. Attention should be paid to content prioritization rather than the awkward and largely meaningless metaphor of a fold.

#####[Adaptive Design:](!adaptive_design)
A web design/development technique in which the layout of a given page changes to fit its environment. Adaptive Design or Adaptive Layout Design is very similar to Responsive Design, however Adaptive Design tends to have a stronger connotation to just front-end (client side) applications where as Responsive Design tends to account for both front and back end (server side) techniques. 

See also: [Responsive Design](#responsive_design), [Fluid Grids](#fluid_grids)


#####[Content First:](!content_first)
A design pattern that starts by laying out a page with only its primary content. Then adding in secondary, tertiary, global and ad content only as and where appropriate. In essence designing from the layout and content out rather than the canvas in. 

AKA Mobile First due to this approach effectively resulting in a well designed mobile experience before discovering the experience for more capable and larger devices.

#####[Context Aware Responsive Experience (CARE):](!context_aware_responsive_experience)
A more descriptive and Mnemonic name for Responsive Experience

#####[Context Buckets:](!context_buckets)
A systematic categorization of User Agent Strings (devices and browsers) into classes that represent certain defined ranges or sets of features, sizes or interaction paradigms such as mobile, touch, mouse-driven, tablet, or camera-enabled.   

#####[Device Buckets: See Context Buckets](!device_buckets)

#####[Device Detection:](!device_detection)
The practice of inspecting the user agent (a unique identifier for a given browser and version) usually for the purposes of inferring a set of available features or device sizes. While legitimate reasons exist for using device detection -- such as to define context buckets on the server -- it has largely become regarded as bad practice in favor of feature detection. 

See also: [Feature Detection](#feature_detection)

#####[Feature Detection:](!feature_detection)
The practice of testing a browser and/or device’s capabilities for specific features as needed. This is much more accurate and “future friendly” and in contrast to the inference of features through device detection. Feature detection, which can include CSS media queries to determine device size, is a key component of creating a responsive website.

See also: [Device Detection](#device_detection)

#####[Fluid Grids:](!fluid_grids)
Most websites are designed on a grid system to give them structure and proportion. Traditionally, those grids have had fixed sizes so they are presented uniformly across all browsers. In a responsive context, this is unworkable so fluid grids are used. Fluid Grids sizes are defined proportionally, often using percentages to allow the structure of the page to properly scale and fit its container.

#####[Graceful Degradation:](!graceful_degradation)
A technique where a site is given an ideal presentation which may utilize new or emerging features. Fall back techniques and styles are then employed for less capable devices and browsers that do not support the more advanced techniques. This ensures that legacy browsers and less feature rich devices still receive an experience that is intentional and well-designed even if it may not match the ideal.

The benefit of this is that content delivery does not suffer at the hands of legacy technologies, and legacy technologies are not taxed with complicated workarounds that would otherwise incur expensive performance hits for the sake of presentational uniformity.

See also: [Progressive Enhancement](#progressive_enhancement)

#####[HTML5:](!html5) (n)
  **Technical**: The 5th major revision of the HTML specification as defined by W3C (World Wide Web Consortium) and WHATWG (Web Hypertext Application Technology Working Group), the relevant standards bodies.

  **Common**: Any combination of the various technologies, specifications, techniques, approaches or trends that have arisen over the last 3-5 years in the area of web design and development which may or may not have anything to do with the technical HTML5 specification. These may include, among others, any or all of the terms herein, as well as what is known as the front-end stack which are HTML, CSS (often CSS3 is conflated with HTML5) and JavaScript. 

Specific popular features of the HTML5 specification or other newer web technologies are also sometimes referred to as HTML5. For example, “HTML5 video,” “HTML5 audio,” canvas, CSS3, local storage, local database, WebGL, WebSockets, etc.

This usage can be compared to the used of the term “Web 2.0” from several years ago. It is meant to describe a paradigm shift in the way the web, or its technologies are used.

#####[Liquid Layouts:](!liquid_layouts) See [Fluid Grids](#fluid_grids)

#####[Mobile First:](!mobile_first) See [Content First](#content_first)

#####[One Web:](!one_web)
The concept of the web is that one piece of content lives at one URL and one URL is the address of one piece of content. 

One Web is a philosophy that asserts that the web is healthier and more useful when paths to content or functionality are not blocked to some users or devices due to a lack of feature support, nor are those paths forked to a subset of users. A common anti-pattern to the concept of One Web is a separate domain and/or navigation hierarchy for the “mobile version” of a web site. Within a One Web philosophy, there would be no “mobile version,” simply a page that presents a context optimized user experience for the same URL.

#####[Progressive Enhancement:](!progressive_enhancement)
A technique where a site is designed for the lowest common denominator device or browser and enhancements are added only when the device or browser is able to support it. 

Much of the benefit that comes from Progressive Enhancement can be achieved with a content first approach to design. Preferring content first and graceful degradation to progressive enhancement also eliminates many of the downsides of progressive enhancement such as having to reverse engineer a design to find its lowest common denominator and then rebuilding back to the ideal.

See also: [Graceful Degradation](#graceful_degradation)

#####[Responsive Design:](!responsive_design)
1. A web design/development technique that rests on the premise that web content is accessed by various devices with various sizes in various contexts and that a web page should be able to respond to all or many of these variables to present the document in a form that is suited to the given context utilizing both front-end (client side) techniques such as layout decisions and deferred loading, and back-end (server side) techniques such as payload adjustments and context bucketing.
2. Any of the various techniques that can be applied to create a web page that responds or adapts to its context.

#####[Responsive Experience:](!responsive_experience)
An experience that takes into account as much of the context in which the end-user is consuming the content in as can be accurately ascertained. This would include all the methods of responsive design and also include things such as interaction paradigms (touch, mouse, voice, gesture based interaction, et al.) bandwidth, user preference and habits, etc.

AKA [Context Aware Responsive Experience](#context_aware_responsive_experience)
