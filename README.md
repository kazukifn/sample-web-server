# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```
[{"breeds":[],"id":"P2iOJ4i15","url":"https://cdn2.thecatapi.com/images/P2iOJ4i15.jpg","width":1280,"height":720}]

[{"breeds":[],"id":"ki","url":"https://cdn2.thecatapi.com/images/ki.jpg","width":900,"height":608},{"breeds":[],"id":"50o","url":"https://cdn2.thecatapi.com/images/50o.jpg","width":372,"height":327},{"breeds":[],"id":"9os","url":"https://cdn2.thecatapi.com/images/9os.jpg","width":2832,"height":4256}]




[{"breeds":[],"id":"P2iOJ4i15","url":"https://cdn2.thecatapi.com/images/P2iOJ4i15.jpg","width":1280,"height":720}]You have mail in /var/mail/kazuki
oonishiikkinoMacBook-Pro:sample-web-server kazuki$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"id":"bg6","url":"https://cdn2.thecatapi.com/images/bg6.jpg","width":500,"height":333},{"breeds":[],"id":"e2a","url":"https://cdn2.thecatapi.com/images/e2a.jpg","width":500,"height":375},{"breeds":[{"weight":{"imperial":"8 - 15","metric":"4 - 7"},"id":"asho","name":"American Shorthair","cfa_url":"http://cfa.org/Breeds/BreedsAB/AmericanShorthair.aspx","vetstreet_url":"http://www.vetstreet.com/cats/american-shorthair","vcahospitals_url":"https://vcahospitals.com/know-your-pet/cat-breeds/american-shorthair","temperament":"Active, Curious, Easy Going, Playful, Calm","origin":"United States","country_codes":"US","country_code":"US","description":"The American Shorthair is known for its longevity, robust health, good looks, sweet personality, and amiability with children, dogs, and other pets.","life_span":"15 - 17","indoor":0,"lap":1,"alt_names":"Domestic Shorthair","adaptability":5,"affection_level":5,"child_friendly":4,"dog_friendly":5,"energy_level":3,"grooming":1,"health_issues":3,"intelligence":3,"shedding_level":3,"social_needs":4,"stranger_friendly":3,"vocalisation":3,"experimental":0,"hairless":0,"natural":1,"rare":0,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/American_Shorthair","hypoallergenic":0}],"id":"MuEGe1-Sz","url":"https://cdn2.thecatapi.com/images/MuEGe1-Sz.jpg","width":3000,"height":2002}]You have mail in /var/mail/kazuki




[
  {
    "breeds": [],
    "id": "b54",
    "url": "https://cdn2.thecatapi.com/images/b54.gif",
    "width": 500,
    "height": 281
  },
  {
    "breeds": [],
    "id": "bth",
    "url": "https://cdn2.thecatapi.com/images/bth.jpg",
    "width": 1024,
    "height": 768
  },
  {
    "breeds": [],
    "id": "e07",
    "url": "https://cdn2.thecatapi.com/images/e07.jpg",
    "width": 600,
    "height": 485
  }
]

Updating Homebrew...
==> Auto-updated Homebrew!
Updated 1 tap (homebrew/core).
==> New Formulae
swig@3
==> Updated Formulae
aws-sdk-cpp         glib                mighttpd2           scons
braid               glooctl             minio               scrcpy
calicoctl           gmic                minio-mc            ship
certbot             graph-tool          nomad               sops
chakra              gst-plugins-good    opa                 telegraf
circleci            hlint               paket               terraform
envconsul           imagemagick         phpunit             topgrade
exiftool            jdupes              procs               vultr
firebase-cli        jfrog-cli-go        pulumi              webpack
flow                joplin              pybind11            whois
fluxctl             knot                pyenv               wildfly-as
folly               libev               rbspy               wtf
gibo                lmod                scalariform         yelp-tools
==> Deleted Formulae
swig@3.04

==> Installing dependencies for jq: oniguruma
==> Installing jq dependency: oniguruma
==> Downloading https://homebrew.bintray.com/bottles/oniguruma-6.9.2.mojave.bott
==> Downloading from https://akamai.bintray.com/c6/c613befafe81da48913ebd1a7eb03
######################################################################## 100.0%
==> Pouring oniguruma-6.9.2.mojave.bottle.tar.gz
🍺  /usr/local/Cellar/oniguruma/6.9.2: 17 files, 1.3MB
==> Installing jq
==> Downloading https://homebrew.bintray.com/bottles/jq-1.6.mojave.bottle.1.tar.
==> Downloading from https://akamai.bintray.com/71/71f0e76c5b22e5088426c971d5e79
######################################################################## 100.0%
==> Pouring jq-1.6.mojave.bottle.1.tar.gz
🍺  /usr/local/Cellar/jq/1.6: 18 files, 1MB
==> `brew cleanup` has not been run in 30 days, running now...
Removing: /Users/kazuki/Library/Caches/Homebrew/openssl--1.0.2r.mojave.bottle.tar.gz... (3.7MB)
Removing: /Users/kazuki/Library/Logs/Homebrew/gdbm... (64B)
Removing: /Users/kazuki/Library/Logs/Homebrew/python... (3 files, 132.6KB)
Removing: /Users/kazuki/Library/Logs/Homebrew/readline... (64B)
Removing: /Users/kazuki/Library/Logs/Homebrew/sqlite... (64B)
Removing: /Users/kazuki/Library/Logs/Homebrew/xz... (64B)
Removing: /Users/kazuki/Library/Logs/Homebrew/openssl... (64B)


```