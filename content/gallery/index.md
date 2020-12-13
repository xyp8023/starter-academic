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



<div class="row" style="margin-top: 5%">
    <h1>Masonry view<tiny><code>?nf_resize=fit&w=300</code></tiny></h1>
    <div class="masonry">
        {{ range $.Site.Data.photos }}
            <div class="item">
                <img src="{{ .src }}?nf_resize=fit&w=300">
                <div class="top-left">{{ .name }}</div>
            </div>
        {{ end }}
    </div>
</div>
