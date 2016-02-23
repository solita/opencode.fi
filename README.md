
Opencode.fi
=============

Työstäminen kesken. gh-pages branch on julkinen heti kun se luodaan, vaikka repository on private.

Lokaalisti saitin voi käynnistää vaikka näin:

```
python -m SimpleHTTPServer 8000
```


------

Opencode.fi is simple listing of Finnish public sector IT projects, which have open sourced their development and published the source code. The service is available in Finnish at [avoinkoodi.fi](http://www.avoinkoodi.fi/) and this is the english language version.

This site lists the publicly available source code for software systems owned and used by Finnish public sector. We do
not intend to list every single source code repository containing some subcomponent or small software library.

## What is this site about?

This site is about helping public sector officials and contractors find the publicly available systems made in Finland.
Finland as a nation will not lose anything if Swedish officials evaluate, or reuse, some of the source code the people of
Finland collectively own. Neither will the Finnish software contractors lose anything. Quite the contrary, Finnish
software companies are quite happy to offer their services if something looks interesting or useful.

The hero Wainamoinen (Väinämöinen) challenges the ancient Antero Vipunen in the [Finnish national epic Kalevala](https://en.wikipedia.org/wiki/Kalevala) thus:

"I shall never, never leave thee
Till I learn thine incantations,
Learn thy many wisdom-sayings,
Learn the lost-words of the Master;
Never must these words be bidden,
Earth must never lose this wisdom,
Though the wisdom-singers perish."


## Why open source is important for the public sector?

Firstly, public sector is by definition spending money collected from the people. The people pay the taxes, so the
people should be allowed to see and use the source code bought with their money. This is a matter of principle. We
can see the buildings and other public projects, we can visit the buildings, and in similar fashion we should see
the systems running behind firewalls and servers. Not all source code can be public though, because some systems are
critical to our safety. This is reasonable. We can't walk to a nuclear plant or military base freely either, and no
one is arguing that's wrong.

Secondly, public sector has unique requirements for their IT solutions. The laws are unique in each country, making
it difficult and sometimes impossible to use product based solutions. We have seen vendor lock-ins and other
malicious practices many times. It's perfectly fine to use products for email servers and such, but complex tailor
made software is the right solution in some cases.

Even though the needs and requirements are unique in each country, they are not totally apart from each other. Inside the
country, each county, university and such officials are subject to same laws and requirements. It would be practical and
reasonable to customize a solution already used by some official elsewhere. This would save money, effort and time. Simply
evaluating another solution is valuable, even if none of the actual source code is reused.

Finally, the public sector doesn't have any commercial interests as such. By definition, public sector is not going to sell and
market their software to anyone.

## How does opencode.fi work?

This GitHub-project contains a web site, available at the address [http://www.opencode.fi/](http://www.opencode.fi/). This web site is published with
the GitHub pages, which means that the content in the [gh-pages branch](https://github.com/solita/opencode.fi/tree/gh-pages) is the content of the web site. Any
pull requests should be targeted to this branch instead of the master branch.

The data is loaded in the web browser with Javascript in JSON-format, which means it's also possible to load the raw data and access it programmatically without the website user interface.

# License

The service and implementation is available under the terms of [Eclipse Public -license](https://github.com/solita/avoinkoodi/blob/master/LICENSE).

