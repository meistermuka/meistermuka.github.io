---
layout: post
title:  "Testing shit!"
date:   2016-02-09 23:34:52 -0500
categories: update
---
Consider this a customary introduction post. I've had "blogs" in the past and attempted to keep them up to date only to lose interest/time within a few weeks.
`ndila like that` is an attempt at self motivation. Hopefully what I post on here will be useful to me and maybe even to others tomorrow or the day after.

{% highlight c %}
void main(void) {
	
	int x, y, x;

	z = x * y;
	// MOAR comments
	printf("The result is %d", z);

}
{% endhighlight %}

{% highlight python %}
def main():
    x = 35
    y = 45
    # MOAR Comments
    print "Doing some stuff"
{% endhighlight %}

{% highlight bash %}
#!/bin/sh
set -e
VERSION="$1"

if [[ "x" == "$1x" ]]; then
  echo "Usage: $0 version"
fi

PACKAGE="mailserve"

/opt/outbox/outlaunch/bin/outdeploy.py -o install .versions/$PACKAGE-$VERSION "$PACKAGE==$VERSION"
rm -f /opt/outbox/$PACKAGE
ln -s /opt/outbox/.versions/$PACKAGE-$VERSION /opt/outbox/$PACKAGE

#/etc/init.d/pdfg restart
{% endhighlight %}