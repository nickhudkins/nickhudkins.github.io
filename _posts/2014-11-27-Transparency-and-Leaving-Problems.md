---
layout: post
title: Leaving Problems Where They Belong
lead-in: Solving problems in the wrong place was expensive and frustrating. So I stopped doing it.
---


Aenean lacinia bibendum nulla sed consectetur. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sed odio dui. Donec ullamcorper nulla non metus auctor fringilla. Etiam porta sem malesuada magna mollis euismod.

Maecenas faucibus mollis interdum. Maecenas faucibus mollis interdum. Nulla vitae elit libero, a pharetra augue. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Donec ullamcorper nulla non metus auctor fringilla.

![Image](https://ununsplash.imgix.net/photo-1416339684178-3a239570f315?fit=crop&fm=jpg&h=725&q=75&w=950)

Nullam quis risus eget urna mollis ornare vel eu leo. Donec id elit non mi porta gravida at eget metus. Praesent commodo cursus magna, vel scelerisque nisl consectetur et. Praesent commodo cursus magna, vel scelerisque nisl consectetur et.

- Thing one is like this
- Think two is like this
- Thing three looks differently

1. This is an ordered list which is great.
2. The second thing in an ordered list can be really nice

{% highlight python %}
import pika


class MessageQueueService(object):

def log(self, message, queue, host, direction=MessageQueueLog.RECEIVED):
message_log = MessageQueueLog.objects.create(
  queue=queue,
  host=host,
  message=message,
  direction=direction
  )
  return message_log
  ...
{% endhighlight %}

> Blockquotes are just the besrt They are amaziingg I certainly think so I like them so much
