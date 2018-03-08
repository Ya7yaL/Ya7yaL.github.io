---
layout: draft
title:  "Test"
date:   2018-03-05 11:09:55 +0100
categories: Draft
---
Firefox has recently implemented a "push notification". 

The problem is I dont really get the point in term of usability nor its functionality. It might had been useful last decade, but with the amount of data of today we deal today, it just spams you click bates and not-so-interesting website news. Or maybe there is a Notification Center lobbyist trying to sell it to companies, I don't know.

Nevertheless, I think it' useless. So I found away to disable it in Firefox 58

- type config:about in the adressbox 
- clic on "I take the risk" when it warns you of the "danger"
- First, disable the push : 
	- search for "push"
	- find dom.push.connection.enabled;  double click on the field to turn it to false
	- find dom.push.enabled; ouble click on the field to turn it to false



- Than, disable webnotifications (not sure if its necessary but I don't need it)
	- dom.webnotifications.enabled;  double click on the field to turn it to false

