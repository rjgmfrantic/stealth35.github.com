---
layout: post
title: Install PEAR on Mac OS X Lion
---

{% highlight bash %}
#sudo cp /private/etc/php.ini.default /private/etc/php.ini
sudo php /usr/lib/php/install-pear-nozlib.phar
pear config-set php_ini /private/etc/php.ini
pecl config-set php_ini /private/etc/php.ini
sudo pear upgrade-all
{% endhighlight %}