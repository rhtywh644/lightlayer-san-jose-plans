# Lightlayer San Jose: Multi-IP Servers, a $4.9 SJ-Lite Cloud and CN2 Dedicated Boxes — Which Plan Do You Actually Need? (All Eight Models, Specs and Price Caveats)

Lightlayer sells three different things out of its San Jose location: eight multi-IP dedicated server models built around bulk IPv4, a budget cloud tier called SJ-Lite Cloud that lists at $4.9/month, and a single-socket E5-2660 dedicated server that can be ordered with a 50 Mbps CN2 route into mainland China. Most visitors only need one of the three, and figuring out which takes about a minute once you see what each line is for.

Pricing is where this gets messy. Per-plan prices for the multi-IP line aren't published on the cart page, promotions from 2024 are still circulating as if they were current, and the cheapest cloud plan and the cheapest dedicated plan differ by more than 10x. What follows is what each line contains, what the numbers you'll find online actually refer to, and where a plan stops being the right buy.

> **The short version**
> - Cheap Linux box for a blog, static site, monitoring or learning: **SJ-Lite Cloud**, 1 vCPU / 1 GB / 50 GB HDD / 500 GB traffic / 300 Mbps / 1 IPv4 at **$4.9/mo**, or **$2.45/mo** with coupon `SJ-LITE245` while launch stock lasts.
> - Dozens to hundreds of IPv4 addresses: **Multi-IPs**, either 1× /24 (253 usable addresses) or 8× /27 (232 usable across 8 separate C-blocks), on 100 Mbps Standard ports.
> - Dedicated cores plus a China-optimized route: **E5-2660 / 16 GB**, 50M CN2 or 100M Standard or 200M Global, 2 IPv4 expandable, around $57/mo with `2026SJE5DS`.
>
> 👉 [Open the San Jose Multi-IP server configurator](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74)

## What the prices floating around online actually mean

The multi-IP cart page prints a single figure at the bottom: "Total Recurring: $196.00 USD Monthly". That number isn't attached to any specific model in the page as it loads, so it can't be quoted as the price of the E3-1230 or the dual E5-2699V3. It tells you the order form was left on some default selection, nothing more.

The only per-model San Jose multi-IP prices Lightlayer has published came from a winter promotion dated 7 November 2024: E3-1230/8G/240G at $148.5 with 253 IPs and $153.9 with 232 IPs, E5-2660/16G/240G at $160.2 and $165.6, and 2×E5-2660 at $176.4 and $181.8. That page also carried a "10% Off San Jose Multi-IP Servers" headline without saying whether those "Now" figures already included the discount. Two years on, treat the range as a rough indication of where the line sat, not as today's quote.

You'll also run into an undated "year-end holiday" summary listing a 2×E5-2660 with 1 Gbps at $70/month against a $648 list price. No date, no conditions, and it doesn't reconcile with any other San Jose listing. Don't budget around it.

For the cloud and dedicated lines the picture is better, because both have named configurations with prices attached. Those are below.

## All San Jose plans at a glance

Eight multi-IP models, all on 100 Mbps Standard bandwidth, all offering the same two IPv4 layouts at checkout (1C = /24, 253 usable; 8C = 8×/27, 232 usable in eight C-blocks). Per-plan prices come from the cart, not from a public price list.

| Model | CPU | RAM | Storage | Order |
| --- | --- | --- | --- | --- |
| San Jose Multi-IPs E3-1230 | E3-1230 | 8 GB | 1 TB HDD / 240 GB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |
| San Jose Multi-IPs E5-2660 | E5-2660 | 16 GB | 1 TB HDD / 240 GB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |
| San Jose Multi-IPs E5-2660 Dual | 2× E5-2660 | 32 GB | 1 TB HDD / 240 GB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |
| San Jose Multi-IPs E5-2660V2/2680V2 Dual | 2× E5-2660 v2 | 32 GB | 1 TB HDD / 240 GB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |
| San Jose Multi-IPs E5-2697V2 Dual | 2× E5-2697 v2 | 32 GB | 1 TB HDD / 240 GB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |
| San Jose Multi-IPs E5-2678V3 Dual | 2× E5-2678 v3 | 32 GB | 1 TB HDD / 240 GB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |
| San Jose Multi-IPs E5-2699V3 Dual | 2× E5-2699 v3 | 64 GB | 2 TB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |
| San Jose Multi-IPs E5-2696/2699V4 Dual | 2× E5-2696 v4 | 32 GB | 1 TB HDD / 240 GB SSD | [Configure](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74) |

The cloud and dedicated tiers, with the price and its date attached:

| Plan | Config | Bandwidth & IPs | Price | Order |
| --- | --- | --- | --- | --- |
| SJ-Lite Cloud (entry) | 1 vCPU / 1 GB / 50 GB HDD | 300 Mbps, 500 GB traffic, 1 IPv4 | $4.9/mo; $2.45/mo with `SJ-LITE245` (launch promo, Sept 2026, 60 units) | [Check current price](https://account.lightlayer.net/?affid=74) |
| SJ-VS04-L (SSD tier, third-party stock listing) | 1 vCPU / 1 GB / 50 GB SSD | 1 TB traffic, 1 IPv4, line marked "Standard" | $9.90/mo, monthly billing (listing checked 19 Oct 2026) | [Check current price](https://account.lightlayer.net/?affid=74) |
| San Jose Dedicated E5-2660 | E5-2660 / 16 GB / 240 GB SSD or 1 TB HDD | 50M CN2, 100M Standard or 200M Global (unmetered), 2 IPv4 expandable | $88/mo list; $57/mo with `2026SJE5DS` (official channel, Sept 2026) | [Open order page](https://account.lightlayer.net/?affid=74) |

## Multi-IP servers: eight models, one job

Every model ships on a 100 Mbps Standard port, and the order page describes IPv4 as "Start from 1C (/29 + /24 × 1)". Two layouts are actually offered: 1C (/24, 253 usable addresses) or 8C (8×/27, 232 usable addresses spread across 8 different C-blocks).

That second option is why this line exists. 232 addresses sitting in eight separate C-blocks look like eight unrelated networks to anything counting subnets, while 253 addresses inside one /24 look like a single allocation. If you're building regional landing pages, running client sites that each need their own address, or doing anything where IP footprint matters, the 8C layout is the product. If you just want the maximum number of addresses and don't care about block diversity, the /24 gives you 21 more.

The processors are older-generation Xeon: E3-1230, E5-2660 and 2660 v2, E5-2697 v2, E5-2678 v3, E5-2699 v3, and E5-2696/2699 v4. Single-thread performance sits well below current server chips, which is normal for a box whose job is hosting a lot of small sites rather than computing hard. Storage is a choice between 1 TB HDD and 240 GB SSD on every model except the 2×E5-2699V3, which comes with 64 GB RAM and a 2 TB SSD.

One caution on the spec sheet: an older 2024 promotion listed the dual E5-2660 at 16 GB, while the current order page says 32 GB. The order page is newer, so 32 GB is what you should expect.

**Who should skip this line.** A single WordPress site, an app backend, a game server or a VPN endpoint has no use for 232 IPv4 addresses, and you'd pay for a resource you can't spend. A cloud instance or one dedicated server costs a fraction of it.

👉 [Compare the eight Multi-IP models and pick your IP layout](https://account.lightlayer.net/?/cart/san-jose-mult-ips-server/&affid=74)

## SJ-Lite Cloud: $4.9/month, or $2.45 during the launch window

SJ-Lite Cloud is the cheapest way into San Jose. The entry plan is 1 vCPU, 1 GB RAM, a 50 GB HDD system disk, 500 GB monthly traffic, a 300 Mbps port and one IPv4, listed at $4.9/month. Coupon `SJ-LITE245` halved that to $2.45/month when the promotion opened at 15:00 GMT+8 on 30 September 2026, limited to 60 units.

Three limits decide whether it suits you:

- **HDD, not SSD.** The low price is built on mechanical storage. A static site, an uptime monitor, a Telegram bot or a learning box won't notice. WordPress with a plugin stack, WooCommerce, or anything doing frequent small writes will.
- **Linux only.** Linux is the only supported system on this plan.
- **No published test IP.** No looking glass or test address went out with the launch, so latency to mainland China, evening-peak packet loss and the real route have to be measured after the box is up, with ping, MTR and traceroute.

Upgrades reach 2 cores and 2 GB RAM, a 50 to 100 GB HDD system disk, up to 1 TB of data disk, 500 to 5000 GB monthly traffic, and up to 20 IPv4 addresses. Extra traffic packages are sold separately, and specific upgrade prices live on the order page rather than in the announcement.

A second, faster San Jose cloud tier exists under a different SKU. A stock tracker checked on 19 October 2026 lists "SJ-VS04-L" at $9.90/month with 1 vCPU, 1 GB RAM, 50 GB SSD, 1 TB traffic, monthly billing, in stock, with the line marked "Standard / unclassified". Channel posts and third-party roundups put a 50 GB SSD / 1 Gbps / 1 TB configuration at roughly $4.9 to $4.95 during promotions. It's a separate product from the HDD SJ-Lite, and nothing suggests `SJ-LITE245` applies to it.

👉 [See what the SJ-Lite Cloud order page is charging right now](https://account.lightlayer.net/?affid=74)

## The E5-2660 dedicated server: three network profiles

San Jose's dedicated line is one configuration: E5-2660, 16 GB RAM, 240 GB SSD or 1 TB HDD, with bandwidth in three profiles. 50M CN2 for mainland China, 100M Standard, or 200M Global. All three are unmetered. You get 2 IPv4 addresses by default, can add more, and can attach high-defense IPs.

Routing as described by a review from May 2026: China Telecom two-way CN2, China Mobile two-way CMIN2, China Unicom outbound direct with CMIN2 inbound. Lightlayer's own product pages don't break it down per carrier, so treat the carrier detail as a claim worth confirming with a traceroute after delivery.

Price: the official Telegram channel lists the E5-2660/16 GB at $88/month, reduced to $57/month with `2026SJE5DS`, and throws in a free upgrade to the 50M Premium (CN2) network. The same ~$57 figure appeared in a review published in May 2026. The code has been reposted since, so it's worth trying at checkout, with the usual caveat that promo codes get withdrawn without notice.

50M here is the port speed. What you actually get to a given Chinese city at 8pm is a separate question, and one only a test will answer.

👉 [Open the San Jose dedicated server order page](https://account.lightlayer.net/?affid=74)

## Picking by situation

- **Personal blog, static site, uptime monitoring, a bot, a place to practise Linux.** SJ-Lite Cloud at $4.9, or $2.45 if the coupon is still live. Nothing else in the San Jose list makes sense at this scale.
- **WordPress with a real plugin stack, a small database-backed app, steady write load.** Skip the HDD SJ-Lite. Take the SSD cloud SKU, or the E5-2660 dedicated server with the 240 GB SSD.
- **A site network, regional landing pages, client sites needing their own addresses.** Multi-IPs with the 8C layout. 232 addresses across eight C-blocks does something a dedicated server with 2 IPs can't.
- **Chinese visitors are the main audience and you need dedicated CPU.** E5-2660 with 50M CN2. This is the only San Jose line where a China-optimized route is documented at all.

The reverse holds too. If you need 8 GB of RAM and two IPs, the multi-IP line is the wrong purchase. If you need 200 IPv4 addresses, stacking cloud instances won't get you there cheaply.

## Before you pay

1. **Read the cart total, not the banner.** `SJ-LITE245` was tied to 60 units and a specific start time; `2026SJE5DS` has been posted in the official channel on and off. Either may be dead by the time you read this, and the only number that matters is the one in the cart.
2. **Confirm disk type and OS.** SJ-Lite is HDD and Linux only. Get either wrong and the $2.45 you saved turns into a migration later.
3. **Ask about refunds and trials.** Nothing in Lightlayer's public terms or product pages states a refund window, a free trial, or an SLA credit policy. Support is the only source, and one email before you pay for a year is cheap insurance.
4. **Plan your own backups.** The terms page is blunt about it: drives are consumables, 100% fault-free operation isn't guaranteed even under hardware RAID10, and Lightlayer isn't liable for data lost to hardware failure. It will help with recovery, not compensate.
5. **Test the network yourself.** For SJ-Lite there's no test IP. Run MTR from your users' region between 8pm and 10pm before committing to a long billing cycle.

Payment methods: cryptocurrency, credit cards, PayPal and Alipay. Anything else, ask support.

## FAQ

**Is the San Jose network good for mainland China?**
Only the dedicated server line documents a China-optimized option (50M CN2). SJ-Lite is advertised with 300 Mbps "optimized" bandwidth, but no test IP or looking glass was published with the launch, so there's nothing verifiable to compare. Measure before committing.

**232 IPs or 253 IPs?**
253 usable addresses arrive as one /24. 232 arrive as eight /27 blocks in eight different C-blocks. If IP diversity is the point of the server, take 232 even though the address count is lower.

**Will $2.45 renew at $2.45?**
Nothing published says the `SJ-LITE245` discount recurs. The "same renewal price" line in Lightlayer's marketing belongs to a 2024 cloud flash sale at $2/month in Hong Kong, Taiwan, Manila, London and Los Angeles, which is a different product. Check the renewal line in the invoice preview before paying.

**Can I run Windows?**
SJ-Lite Cloud is listed as Linux only. The dedicated server listings don't state an OS restriction, but Windows licensing isn't mentioned anywhere either, so confirm with support first.

**Can I add IPs or DDoS protection later?**
SJ-Lite supports up to 20 IPv4 addresses per instance according to its spec sheet, and extra traffic packages are sold separately. The dedicated server includes 2 IPv4, expandable, with high-defense IPs available. On the multi-IP line you pick 253 or 232 at order time.

## Final call

Three lines, three buyers. A cheap Linux box for a personal project: SJ-Lite Cloud, where $2.45 versus $4.9 is a coupon question rather than a product question. More than a hundred IPv4 addresses across separate C-blocks: the multi-IP line in the 8C layout. Dedicated cores with a route that's actually tuned for China: the E5-2660 with 50M CN2.

One last step before you click: open the cart with the plan you want selected and read the recurring total plus the renewal line. That number, not this article and not a two-year-old promo page, is what you'll pay.

👉 [Check current San Jose pricing and start an order](https://account.lightlayer.net/?affid=74)
