+++
title = "Hello World"
date = "1986-09-20"
author = "Elliot"
cover = ""
description = ""
tags = ["Hello", "World"]
+++

> "Hello, friend?" That's lame.
> Maybe I should give you a name...
> But that's a slippery slope.
> You're only in my head.
> We have to remember that...
> Shit.
> It's actually happened.
> I'm talking to an imaginary person.
>
> **— Mr. Robot S01E01**

{{< tabs >}}
{{% tab name="python" %}}
```python
print("Hello World!")
```
{{% /tab %}}
{{% tab name="R" %}}
```R
> print("Hello World!")
```
{{% /tab %}}
{{% tab name="Bash" %}}
```Bash
echo "Hello World!"
```
{{% /tab %}}
{{< /tabs >}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ornare risus ut
rutrum tincidunt. Quisque lacinia venenatis enim, sed tincidunt mauris mollis
a. Ut nec leo urna. Vivamus eget velit quam. Maecenas in mollis diam. Etiam
ullamcorper dolor at tincidunt rutrum. Suspendisse posuere nisi nec elit
ultricies vulputate. Nam commodo semper facilisis.

{{< notice note >}}
A notice disclaimer
{{< /notice >}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ornare risus ut
rutrum tincidunt. Quisque lacinia venenatis enim, sed tincidunt mauris mollis
a. Ut nec leo urna. Vivamus eget velit quam. Maecenas in mollis diam. Etiam
ullamcorper dolor at tincidunt rutrum. Suspendisse posuere nisi nec elit
ultricies vulputate. Nam commodo semper facilisis.

{{< notice info >}}
An information disclaimer
{{< /notice >}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ornare risus ut
rutrum tincidunt. Quisque lacinia venenatis enim, sed tincidunt mauris mollis
a. Ut nec leo urna. Vivamus eget velit quam. Maecenas in mollis diam. Etiam
ullamcorper dolor at tincidunt rutrum. Suspendisse posuere nisi nec elit
ultricies vulputate. Nam commodo semper facilisis.

{{< notice tip >}}
A tip disclaimer
{{< /notice >}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ornare risus ut
rutrum tincidunt. Quisque lacinia venenatis enim, sed tincidunt mauris mollis
a. Ut nec leo urna. Vivamus eget velit quam. Maecenas in mollis diam. Etiam
ullamcorper dolor at tincidunt rutrum. Suspendisse posuere nisi nec elit
ultricies vulputate. Nam commodo semper facilisis.

{{< notice warning >}}
A warning disclaimer
{{< /notice >}}

## Header 2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam nec interdum metus. Aenean rutrum ligula sodales ex auctor, sed tempus dui mollis. Curabitur ipsum dui, aliquet nec commodo at, tristique eget ante. **Donec quis dolor nec nunc mollis interdum vel in purus**. Sed vitae leo scelerisque, sollicitudin elit sed, congue ante. In augue nisl, vestibulum commodo est a, tristique porttitor est. Proin laoreet iaculis ornare. Nullam ut neque quam.

> Fusce pharetra suscipit orci nec tempor. Quisque vitae sem sit amet sem mollis consequat. Sed at imperdiet lorem. Vestibulum pharetra faucibus odio, ac feugiat tellus sollicitudin at. Pellentesque varius tristique mi imperdiet dapibus. Duis orci odio, sodales lacinia venenatis sit amet, feugiat et diam.

### Header 3

Nulla libero turpis, lacinia vitae cursus ut, auctor dictum nisl. Fusce varius felis nec sem ullamcorper, at convallis nisi vestibulum. Duis risus odio, porta sit amet placerat mollis, tincidunt non mauris. Suspendisse fringilla, `odio a dignissim pharetra`, est urna sollicitudin urna, eu scelerisque magna ex vitae tellus.

```css
/* PostCSS code */

pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;

  @media (--phone) {
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  code {
    background: none !important;
    color: #ccc;
    padding: 0;
    font-size: inherit;
  }
}
```

```js
// JS code

const menuTrigger = document.querySelector('.menu-trigger')
const menu = document.querySelector('.menu')
const mobileQuery = getComputedStyle(document.body).getPropertyValue('--phoneWidth')
const isMobile = () => window.matchMedia(mobileQuery).matches
const isMobileMenu = () => {
  menuTrigger.classList.toggle('hidden', !isMobile())
  menu.classList.toggle('hidden', isMobile())
}

isMobileMenu()

menuTrigger.addEventListener('click', () => menu.classList.toggle('hidden'))

window.addEventListener('resize', isMobileMenu)
```

```html
<!-- HTML code -->

<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

#### Header 4

Curabitur scelerisque felis viverra varius scelerisque. Ut enim libero, molestie gravida blandit at, mollis ornare tellus. Cras arcu mi, ultrices vel pulvinar vel, volutpat eu tortor. Nullam nec eros quis massa ultrices iaculis sed in metus. Praesent sollicitudin sem sit amet orci tempor gravida.

- Maecenas elementum vitae nibh vitae porttitor.
- Aenean consequat, risus ut cursus placerat, arcu nulla sodales risus, ut molestie tellus tellus et dui.
- Integer imperdiet turpis vitae lacus imperdiet, ut ornare ligula auctor. Integer in mi eu velit vehicula suscipit eget vulputate nulla.
- Etiam vitae enim quis velit lobortis placerat a ut sem.
  - Curabitur lobortis ante sit amet orci pulvinar, sollicitudin viverra nunc accumsan.
  - Praesent fermentum orci quis leo facilisis posuere.

Aliquam erat volutpat. In hac habitasse platea dictumst. Nunc ut tincidunt mauris. Sed at gravida risus, id semper magna. Nullam vitae enim mattis, sodales neque non, pharetra elit. Cras sit amet sagittis augue, et finibus turpis. Ut tempus tincidunt diam vel pharetra. Nulla porttitor odio sit amet nulla scelerisque, quis aliquam mi imperdiet. Sed tincidunt dui vel tellus vestibulum rhoncus. Donec tempus ultrices velit.

