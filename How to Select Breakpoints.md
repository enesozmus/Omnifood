# How to Select Breakpoints

> - What actually are **breakpoints**?
> - Well, **breakpoints** are the viewport with at which we want or designed to change, or in other words **breakpoints** are the pixel values that we want to put in all media queries.
> - ♫ First, when we optimize for one very specific device, we ignore all the other users of the other devices.
> - ♫ And second, and even more important maybe, is that this strategy is an absolute nightmare for maintaining your code, and keeping it up to date in the future. And so that's why we call this **the BAD strategy**, and therefore we need another one.

> - So the next strategy is what I call **the GOOD strategy**. And this one is based on screen width ranges.
> - So basically what we do here, is to look at the most used width for different categories of devices like phones, or tablets, or desktop computers, and then we try to group them together in some logical way to then pick our **breakpoints** from that.
> - And so this is already a lot better than the first strategy, because we're not setting **breakpoints** at one specific device, but between similar device sizes.
> - So we can assume that most phones are somewhere between 300 and 500 pixels, and that most tablets are between 600 and 900 pixels. And so therefore we can place a **breakpoint** somewhere at 600 pixels.
> - And the same works for other categories. So for example, most landscape tablets are between 900 and 1100 pixels, and desktops are usually above 1200 pixels. And so we can put a media query, for example, at 1200 pixels.

> - All right, so again, this is already a much much better strategy than the first one, but we can make it even better by combining this with the perfect strategy. And the perfect strategy is basically all about setting **breakpoints** at places where **the design breaks down**.
> - So in this strategy, we can try to completely ignore devices and device categories all together, and only look at our content and our design.
> - So we begin at one screen size, either desktop, or mobile size, and then we start decreasing our screen width, or increasing it for mobile first.
> - Then as soon as the design breaks, so which means that the design no longer looks acceptable, we create a new breakpoint, and that's it.
> - So again, what we do in this **PERFECT strategy**, is to just put the **breakpoints** wherever the design starts to look weird, and like out of place, and try to not think about devices at all.
> - Now, it's actually quite hard to do this one completely without thinking about devices. So without classifying breakpoints as a phone, or as a tablet, or something like that.
> - So therefore, basically, we're gonna use this **PERFECT strategy** together with **the GOOD strategy**.
