LAGUNYAPRINT - CONTENT ACCURACY FIX
===================================
13 HTML files. No images. One push.
This replaces the earlier "City Fix" package - do not push that one
separately, everything from it is included here.

WHY THIS MATTERS
----------------
Your site was making claims that came from the original template, not
from you. A corporate client who reads these and then finds out the
truth stops trusting the quote you just sent them.

WHAT WAS WRONG AND WHAT IT SAYS NOW
-----------------------------------
1. "Find a LagunyaPrint Store Near You - Explore 40+ LagunyaPrint
   outlets across India", listing Bangalore, Chennai, Gurugram,
   Hyderabad, New Delhi and Pune.
   You have one shop.
   NOW: "Same Day Delivery Areas" with Indirapuram, Ghaziabad, Noida,
   New Delhi, Gurugram, Faridabad.

2. Delivery claims for Bengaluru, Hyderabad, Chennai and Pune in the
   orange top bar and in two FAQ answers.
   NOW: "Same Day Delivery across Delhi NCR - Pan-India Shipping", and
   the FAQ lists Delhi NCR areas with courier elsewhere in India.

3. Four FAQ answers referred to a checkout: "Enter your PIN code during
   checkout", "displayed at checkout before you confirm", "Choose Store
   Pickup ... during checkout", "Shipping costs calculated at checkout".
   Your site has no checkout - orders come through WhatsApp.
   NOW: all four rewritten around WhatsApp and shop pickup.

4. Dead links that went nowhere: "Store Locator", "New Launches",
   "Blog" in the menu, and "Track Order" in the footer.
   NOW: replaced with real pages, and "Order on WhatsApp" in the footer.
   The site now has ZERO dead links on all 13 pages.

STILL NEEDS YOUR DECISION
-------------------------
Every page shows "Google Review - 4.5 Star Rating". I cannot verify
whether that is your real rating. If your Google Business Profile does
not actually show 4.5, tell me and I will remove or correct it. A made-up
rating on a website is a real legal and trust risk.

INSTALL
-------
Copy these 13 files into D:\LagunyaPrint-website, overwrite, then:
    git add -A
    git commit -m "Correct delivery claims, remove false store claims and dead links"
    git push origin main
Then lagunyaprint.in -> Ctrl+Shift+R

ROLLBACK
--------
Netlify -> Deploys -> deploy edca6c9 -> "Publish deploy"

NOTE ON NETLIFY CREDITS
-----------------------
Each production deploy costs 15 credits out of your 300/month.
Batch your changes and push once, not three times.
