---
layout: post
title:  "The Art of MVP Testing"
date:   2014-10-31 11:21:21
categories: testing
---

<p>Done is better than perfect. Don't worry be crappy. Quotes propagated over and over again in our 'fail fast and fail often' age. I don't think there's anything wrong with the metaphors but we should be cautious about their exact definitions, more so when it comes to testing new apps before they are launched for the first time.</p>

<p>Testing is one of those areas that is often overlooked when developing apps particularly in the MVP stages. There's a lot of literature about writing automated testing which makes it seem like we've entered a new era in software engineering which doesn't require 'old skool testing'. What I mean by 'old skool testing' is the process of simply going through your app firsthand and checking each feature just to make sure it works.</p>

<p>Many app owners are actually not checking their own apps because they're too busy with other portions of the business. There's also a notion that if the app development is outsourced, it suddenly becomes the responsibility of the outsourced party to test it before it goes into production. This is true only to a certain point. The app owner, specifically startups coupled with investor pressure, want to ship as soon as possible.</p>

<p>Many new app owners or startups postpone testing early on and end up paying for it painfully as they progress. All of a sudden a cool app turns into a nightmare not just for the users but more so for the founders. Many founders don't consider the pyschological toll of working on a buggy app from the outset. It affects the general mood and morale of the company and can potentially lead to the downfall of the business. Testing is that butterfly effect that eludes many founders.</p>

<ul>
  <li><b>Less is good enough</b></li>
    <p>Guy Kawasaki argues that you should get an app to a level where it's 'good enough'           and worry about testing or perfecting it later because you need to focus on getting cashflow in. My opinion is 'less is good enough'.Trim the scope of your MVP to its bare essentials - zone in on delivering the core product. Many founders still want to pack in a load of features at the MVP level. If it means not having authentication in the first spiral, do it. You have to be ruthless at knowing what's achievable with the resources at hand in the timeframe you're aiming for. Many people don't realize this but getting the scope of your MVP right early on, takes half the work out of testing.</p>

  <li><b>Break it up</b></li>
    <p>Testing tends to happen at the end of a spiral and when that happens things aren't tested well because there's a lot to test. My recommendation is break it up into more manageable chunks, potentially even a simple checklist to apportion various sections and scenarios will help make the fixes more organized.</p>


  <li><b>Test together</b></li>
  <p>Everyone testing together makes it more fun as opposed to doing it by yourself. I try to bring everyone on board, both developers & clients to do it at the same time so we can identify, organize and solve quicker.</p>

  <li><b>Don't mess with payments</b></li>
  <p>If your app needs to accept payments from the outset don't fool around. Payments need to be work. Otherwise users will not return. Plain and simple. At the very least you need have a log setup for all payments and do test transactions (not within the code but actual user payments) before going to market. If your app is international this is more important because not all credit cards work with all gateways so you might end up changing gateways right before launching.</p>

  <li><b>Grammatical errors</b></li>
  <p>Not directly related to testing but critical to a flawless launch and one of my biggest pet peeves when launching an app (not blog posts :P) is having grammatical errors. This is the pin that pops the balloon. Your sexy app is no longer sexy. This is especially critical for international apps where the founders don't have a good grasp of English. All it takes is 30 minutes to scan the app and correct these errors.</p>
</ul>
