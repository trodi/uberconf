building native apps with js
============================
TripLingo uses it
startup weekend - everyone there gets 1 min to pitch an idea, keeps widdling down. 
from friday night to end of sunday you work on it. competition etc

Titanium
--------
provides a native js runtime / bridge
_all native, no code generation_
open source, has backing company
don't take a lowest common denominator approach
> Write once, adapt to ios and android
will only load glue code modules that is needed for your app 

everything built into the os is there for you
can add titanium _wrapper_ to hook into something not bridged by titanium
can add a webview into your app to hook into web libs, if needed
things that don't require the DOM, easy drop in (no webview required)

* testflight - you upload a signed binary to this site, then it notifies all testers that and allows
them to download and install newest test build
* flurry - aggregates user metrics

can fully run output in xcode etc.
near native performance
want to minimize constantly going into native layer and back to js layer (marshalls/unmarshalls)

> always have to learn the native toolchain

projects that hot deploy to phones and emmulators
* xlite
* tishadow - better

joli - ORM layer for titanium
much improved sdk etc. today

questions
---------
easy to muck with the file system?
why did they choose js for titanium as the language? 