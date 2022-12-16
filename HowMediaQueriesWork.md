# How Media Queries Work?

> - So let's say that we wanted to apply a certain style for the range between **zero** and **600 pixels**. So then we could write a media query like this:
> - - **@media(max-width: 600px)**
> - So basically, this media query checks if the current viewport width a smaller or equal than 600 pixels:
> - - **? currentViewport <= 600px**
> - And if it is small, then all the CSS code that is in this media query will apply.
> - And if not, well, then that code that is in the media query will not apply.
> - Now after 600 pixels, for example, at 700 pixels, it stops working. So the code is no longer gonna be applied then.

> - So for example, if we wanted to cover the space **from zero to 1200 pixels**, we would write a media query like this:
> - - **@media(max-width: 1200px)**
> - So now we have mix-width to 1200 pixels, and so this media query basically asks the question, is the width less or equal than **1200 pixels**? And so if it is, then of course, this code that is in this media query will be applied.

> - Now inside these media queries here, we simply override some specific parts of the **global CSS**, so the code that is outside of any media query. But all the rest of the global code will of course, still apply.
> - And so you can think of media queries as tools for basically overriding specific parts of our CSS at certain viewport width.

> - But anyway, switching back to our two media query examples here, maybe you are wondering what happens if for example, a certain phone has a width of 400 pixels. So which media query will apply now in this situation? And that is of course an excellent question, and the answer is indeed simple. So both queries will apply because both of the conditions are actually true, right? So these 400 pixels are less than 600 pixels and they're also less than 1200 pixels. And so the code in both media queries will be applied.
> - Now if you have conflicting CSS declarations in these queries, which is in fact usually the case, then the one which appears less in the code is the one that will apply.

> - Media Query kullanmak, masaüstü bilgisayarlara, dizüstü bilgisayarlara, tabletlere ve cep telefonlarına uyarlanmış bir stil sayfası sunmak için kullanılan popüler bir tekniktir.
