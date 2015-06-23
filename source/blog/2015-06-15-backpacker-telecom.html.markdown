---
title: Backpacker Telecom
date: 2015-06-15 14:00 UTC
tags: Lison, TADHack
masthead: "15-6-15.jpg"
published: true # Don't publish me when building
---

I have spent the last weekend in Lisbon Portugal after an invite from @sammachin
to attend TADHack at the Institute of Superior Technology.

During the hackday I built a little hack to help me stay connected while
traveling without breaking the bank using Truphone, Twilio and local data sims.

The hack even won a $100 prize from Truphone.

It works like this:

- My O2 sim has unconditional call divert set to a UK based Twilio Number
- The Twilio number redirects forwarded calls my Truphone number
- I also can call or text an access number from any other phone to have my calls diverted to that number for 24 hours

This means I have a lot more control over my roaming costs and can decide how to take / make calls.

- Timezone based call control (no more 4am PPI calls)
- PayPhone reverse call. (call a number and get Twilio to call me back for 'free' calls)

The tidied up code is up on github at (github.com/kevinprince/telecom).

I have the rest of the week in Lisbon to rest-up and get ready to head to Asia.
