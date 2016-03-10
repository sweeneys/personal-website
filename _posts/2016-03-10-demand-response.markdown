---
layout: post
title:  "Demand response"
categories: jekyll update
date:   2016-03-10
comments: true
folder: /blog-2
excerpt_separator: <!--more-->
---

9 weeks ago I started my current internship with EnerNOC. Last week, the UCD engineering ball
took place which was the first large gathering of current UCD engineering students in those 9 weeks. Predictably, the 
first question everyone asked each other was "How is your internship going?". <!--more--> More often than not
I also got a follow up question which was "So what does your company actually do?". I really enjoyed
answering the question so I decided to write a blog post about it.

**Demand response**

I am by no means an expert in the area but in this blog post I will attempt to give some general ideas
about demand response that have helped me to understand the concept and its larger significance.

Electricity cannot (yet?) be stored conveniently on a large scale. This means that at any given time the
amount of electricity that is produced (supply) must equal the amount of electricity that is consumed 
(demand). This makes it really important to know in advance what demand will be, to make sure
that there will be adequate supply.

In the past, ensuring that there was adequate electricity supply meant having a reasonable degree of confidence
in your electricity demand forecast and making sure that all your coal/nuclear/oil/gas fired power plants were
turned on and able to vary their outputs slightly if the reality ended up being different from what had been
forecasted. 

Enter renewables! Wind power generated 24% of Ireland's overall electricity in 2015. Wind is *free* energy, 
renewable (it won't run out) and generating electricity from wind doesn't release carbon into the atmosphere 
(greenhouse gas). 
But there are some problems with wind. One issue is that wind is intermittent, which means that wind doesn't 
blow all the time. This means we have to have back-up sources of power for the days when it isn't windy. Another issue is that
even though spatial and temporal forecasts of wind speed and direction have improved hugely in recent years,
they are still not perfect. This makes it difficult to know in advance exactly how much power will be generated 
from wind.

If wind speed is forecast to be 12 m/s and then ends up being 6 m/s (wrong by a factor of 2) this will translate 
to wind power being 8 times less than what was forecast (wind power changes with the cube of wind speed - see
equation below). This means that even slight errors in wind speed forecasts can lead to very different
amounts of power being generated from wind.

![wind power speed]({{ site.url}}/shaun-and-jekyll/assets/img/blog/blog-2/thumb.jpg) 

**When supply is in danger of not equalling demand**

For this reason, high amounts of wind power generation makes it difficult to ensure that supply equals demand. In the case where a 
wind power forecast is less than expected, this means overall supply will be less than expected which means that 
supply will be less than demand. In the past, the default option for this case was to 
increase supply to cover the shortage.
What this meant practically was to turn on a quick-starting and extremely expensive gas-fired *peaking power plant*.

Demand response introduces an alternative option - to instead decrease demand to fill the gap. The way this works is 
that energy users (households or small & large companies) reduce their electricity consumption 
in times of shortage. As an example, a large company could turn off one of their energy intesive processes. This 
action restores the supply-demand balance without having to turn on any extra power plants and maintaining the 
stability of the electricity grid (no blackouts/the lights stay on).

**Big picture**

The example I gave above where a large company turns off one of its processes to reduce demand to balance supply
is only one way demand response works. In the future all electricity customers will be able to 
participate directly in demand response. We can do this by reducing electricity consumption in our homes 
at peak times. 

Did you also know that another problem is when there is too much electricity being generated and not enough 
being consumed? In Ireland this usually happens on a windy night when there is very little electricity 
demand since everyone is sleeping. Demand response has
a solution for this situation too - to increase electricity demand. 
This could be a company starting a manufacturing
process at night time or a household turning on their tumble dryer in the middle of the night (or turning on their
electric car to charge? soon...).

Demand response means that expensive new peaking power plants that are rarely used do not need to be built. 
Demand response increases engagement of participants on the demand side and promotes energy efficiency. 
Demand response provides a valuable resource to electricity grid operators in times of system instability 
and therefore reduces the likelihood of blackouts. 

Overall, demand response is a small part a big puzzle in transitioning towards a more flexible electricity grid which
prioritises the integration of renewable energy.