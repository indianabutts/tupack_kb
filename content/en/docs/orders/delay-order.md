---
title: Delaying Despatch of an Order
date: 2017-01-05
description: >
  There are times when you want to delay an order from going out to your customers. Find out how to achieve that.
categories: [Examples]
weight: 2
tags: [test, sample, docs]
---

{{% alert title="Note" %}}If a request is submitted after 2pm, we cannot guarantee that the order has not already been despatched{{% /alert %}}

To delay an order, you should submit a request via our Success Portal, or via the form below. Make sure to include the order number and expected despatch date in the request.

<div id="formkeep-embed" data-formkeep-url="https://formkeep.com/p/42ed08364d58234212d116c0f747a0b1?embedded=1"></div>

<script type="text/javascript" src="https://pym.nprapps.org/pym.v1.min.js"></script>
<script type="text/javascript" src="https://formkeep-production-herokuapp-com.global.ssl.fastly.net/formkeep-embed.js"></script>

<!-- Get notified when the form is submitted, add your own code below: -->
<script>
const formkeepEmbed = document.querySelector('#formkeep-embed')

formkeepEmbed.addEventListener('formkeep-embed:submitting', _event => {
  console.log('Submitting form...')
})

formkeepEmbed.addEventListener('formkeep-embed:submitted', _event => {
  console.log('Submitted form...')
})
</script>
