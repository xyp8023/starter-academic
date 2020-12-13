Beach, Tel Aviv
![image](/images/telaviv.jpg)

Barcelona
![image](/images/barcelona.jpg)

Heaven Lkae, Changbai Mountains
![image](/images/changbaishan.jpeg)

Gullmarsfjorden
![image](/images/gullmarsfjorden.jpg)

Barbecue, Kungshamra
![image](/images/barbecue.jpg)

Jellyfish
![image](/images/jellyfish.jpg)

Hugin:
![image](/images/hugin.jpg)

Aurora, Stockholm
![image](/images/aurora.jpg)


<img src="/images/aurora.jpg" alt="image" width="4000"/>
<img src="/images/barbecue.jpg" alt="image" width="4000"/>



{{ $page := .Site.GetPage "/gallery" }}
{{ $images := $page.Resources.ByType "image" }}

{{ range $images }}
  {{ $original := . }}
  {{ $resized := .Resize "400x" }}
  <p>
    <a href="{{ $original.Permalink}}">
      <img src="{{ $resized.Permalink }}"/>
    </a>
  </p>
{{ end }}
