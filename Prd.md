PRD: Lost & Found Platform 
1. The Problem We're Solving
Losing something important your wallet, keys, laptop, or ID is stressful enough. Trying to get it back shouldn't make it worse.
Right now, most lost-and-found setups are broken on both sides:
• For the person who lost something: You have no idea where to look. You end up calling three different reception desks, scrolling through messy community group chats, and describing your black backpack to five different .
• For the staff and finders: Logging items in a paper binder or a basic spreadsheet takes too long, descriptions are vague and nobody knows where the item is and the front desk staff spend a lot of time answering calls from people with lost items.

The goal is to build a simple, central place where anyone can log a found item in under a minute, and owners can search, prove an item is theirs, and pick it up without the usual runaround.
2. Who We're Building This For
• The Seeker : Anxious, in a hurry, and probably checking their phone while retracing their steps. They want to know immediately if their stuff has been found, or set an alert so they don't have to keep refreshing a page.
• The Finder: Someone who picked up a dropped phone or wallet and wants to do the right thing as long as it doesn't take ten minutes or force them to create an account and verify an email.
• The Admin : Receptionists, security guards, or operations staff managing the physical storage room. They need to log drop offs fast, keep shelves organized, and make sure they don't accidentally hand a lost item to the wrong person.
3. How It Should Work 
Logging a Found Item 
If reporting a found item feels to stressful or tedious  people won't use it.
• No-Account Guest Reporting: A Finder should be able to scan a QR code on a poster (or open the web app), snap a photo, pick a category, and hit submit. No password required.
• Smart Photo Intake: Photos are mandatory for found items a picture saves a thousand words. When a photo is uploaded, the system should suggest basic tags (e.g., Electronics, Black, Headphones) so the user just taps to confirm instead of typing.
• Auto-Blurring Sensitive Info: If someone finds a driver's license, passport, or credit card, we cannot blast their home address or card number on a public feed. The system should flag IDs/cards and automatically blur sensitive text before the listing goes live.
• Location Pinning: A quick dropdown of common buildings/zones plus an optional map pin so owners know where it turned up.
B. Searching & Smart Matching
• Clean Public Catalog: Seekers can browse found items with simple filters: What is it?  When did you lose it? , Where? , and What color?
• Lost Item Alerts: If the item isn't in the system yet, the Seeker can post a quick "Lost" report. Behind the scenes, our matching engine watches incoming "Found" reports. The second something matches the category, keywords, and timeframe, the Seeker gets an email or SMS nudge: "Hey, someone just turned in a silver ring near the library take a look."
• Clear Status Tracking: Nobody likes being left in the dark. Every item moves through clear stages visible to the people involved: Reported \rightarrow At Front Desk \rightarrow Claim Under Review \rightarrow Ready for Pickup \rightarrow Returned.
C. Proving Ownership & Handoff
This is the trickiest part: showing enough info so the real owner recognizes their stuff, while holding back enough detail so scammers can't claim freebies.
• The "Secret Detail" Gate: When someone clicks "This is mine," they have to answer a prompt before the claim goes through. Finders or staff can set a custom question (e.g., "What's the lock screen photo?" or "What's inside the front pocket?"), or the Seeker has to provide unique proof like a serial number or distinctive scratch.
• One-Time Pickup Pass: Once staff approve a claim, the Seeker gets a unique QR code or 4-digit PIN. When they show up at the desk, staff scan/enter the code, check a photo ID if it's a high-value item, and close out the ticket.
D. Back-Office Storage Management (For Staff)
• Bin & Shelf Tracking: When an item is handed over to staff, the system generates a unique Item ID  Staff can print a small sticker label or just write  a tag and assign it to Shelf B, Bin 3. No more digging through three boxes of umbrellas while an owner waits at the counter.
• Expiration & Cleanup Rules: Storage closets fill up fast. Staff can set retention rules (e.g., 30 days for low-value items, 90 days for electronics). The dashboard flags expired items so staff know what can be donated, recycled, or cleared out.

5. Edge Cases & Real-World Messiness
• High-Value vs. Everyday Stuff: A laptop needs stricter checks than an  umbrella. Admins should be able to mark certain categories as "High Value," which forces an in-person government ID check at pickup.
• Items Found by people  Hold of Them: Sometimes a Finder logs an item ("Found a black lab mix" or "Found keys on somewhere and holds onto it instead of dropping it at a central desk. We should support a "Held by Finder" handoff option with in-app messaging (masking phone numbers) so they can coordinate a safe public meetup.
• Duplicate Reports: Three people might report the same unattended backpack. Staff need a quick way to merge duplicate listings into one active record.
• Spam & Bogus Claims: If an account submits three rejected claims in a row, flag or temporarily lock their claiming privileges so bad actors can't guess answers repeatedly.
6. How We'll Know It's Working (Metrics)
• Return Rate: What percentage of logged found items actually make it back to their owners? (Our north star metric).
• Intake Speed: Average time from opening the "Report Found Item" screen to hitting submit. Target: under 60 seconds.
• Resolution Time: Median time from an item being logged to being marked Returned.
• Staff Time Saved: Reduction in manual phone/email inquiries handled by front-desk staff.
