# Cheapest Windows VPS: Is $2.99 a Month Real, What Does €5.50 Buy, and What Will the First Year Actually Cost? (Plan Table + Billing Traps)

Evoxt lists a Windows VPS at $2.99 a month, the lowest verified Windows price in this comparison. Contabo's cheapest Windows plan sits at €5.50, OVHcloud starts at US$8.50 and IONOS advertises $16. Those four numbers describe four different products, and only some of them are prices you can keep paying.

The differences that matter are not in the specs column. Contabo's €5.50 is a first-24-months rate, IONOS's $16 covers three months inside a one-year contract, and OVHcloud quotes before tax. Read as monthly costs, they understate a year by amounts large enough to reorder the shortlist. What follows is every Evoxt plan as listed, what the cheapest tiers can realistically run, and the first-year arithmetic most price roundups skip.

## Quick pick: which tier is worth your money

> Most budget buyers should skip the $2.99 plan. VM-1 at $5.99 (1 vCore, 2 GB RAM, 20 GB storage) is the smallest Evoxt Windows plan with room for an actual desktop session, and VM-2 at $11.99 (2 vCore, 4 GB RAM) is the one that survives a browser with several tabs plus Office. If you only need a box to sit logged in and run one script, VM-0.5 at $2.99 gets you there and nothing more.
>
> 👉 [Check the current Evoxt Windows VPS plans and monthly prices](https://bit.ly/EvoXt)

## Every Evoxt Windows plan, listed

| Plan | vCPU / RAM | Storage | Price (monthly) | Order |
| --- | --- | --- | --- | --- |
| VM-0.5 | 1 vCore / 512 MB | 5 GB | $2.99 | [Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 vCore / 1 GB | 10 GB | $4.99 | [Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 vCore / 2 GB | 20 GB | $5.99 | [Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 vCore / 2 GB | 20 GB | $6.95 | [Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 vCore / 4 GB | 30 GB | $11.99 | [Deploy VM-2](https://bit.ly/EvoXt) |
| VM-4 | 4 vCore / 8 GB | 60 GB | $23.99 | [Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 vCore / 8 GB | 60 GB | $29.99 | [Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 vCore / 16 GB | 80 GB | $47.99 | [Deploy VM-8](https://bit.ly/EvoXt) |

The 512 MB tier is the one that makes the $2.99 headline possible, and it is also the one to think hardest about. Windows with a remote desktop session loads a graphical shell, a browser and whatever else you install; 512 MB leaves very little for any of that. Treat VM-0.5 as a licence plus a test box. VM-0.75 doubles the RAM for $2 more, and VM-1 doubles it again for one dollar on top of that, which is why the third row is where most people land.

Note that VM-6 and VM-8 both carry 8 vCores. The $18 gap buys RAM, not cores, so pick between them on memory pressure rather than CPU count.

## What the monthly fee covers, and what it doesn't

Evoxt includes a few things that competitors charge for separately or sell as add-ons:

- **Weekly offsite backup on every VM at no cost.** Contabo treats automatic backup as a paid add-on; Liquid Web bundles it into a managed price that starts at $54.
- **Browser-based VNC console** for when RDP stops answering, useful during firewall mistakes.
- **Firewall rules managed outside the VM**, plus IP reassignment and floating IPs, VM cloning and basic monitoring in the control panel.

Paid extras are listed separately: an additional IP address at $3 a month, an extra vCore at $3 a month, an extra 1 GB of RAM at $2 a month, and additional monthly transfer at $3 per TB on the standard network, $12 per TB on premium and $24 per TB on premium plus. Payment methods accepted are credit and debit cards, PayPal, Bitcoin and USDt Tron. Billing terms run from monthly up to three years, and you can top up account credit and let it settle future invoices.

Locations are split into tiers. The standard network covers the United States, United Kingdom, Canada, Germany, Poland, Amsterdam, Tokyo, Malaysia and Australia. Premium network locations are Hong Kong and Osaka, with a separate Malaysia premium tier. If your workload talks to mainland China, the Hong Kong and Osaka options are the ones to price first, because transfer on premium networks costs four to eight times the standard rate.

Evoxt's pricing page leads with single-core performance, quoting CPU frequency up to 6.0 GHz+. That is the vendor's headline claim about its hardware, not a guarantee that every core sustains that clock, so judge it by the workload you're buying for rather than the number.

👉 [Compare Evoxt's plan sizes against your RAM needs](https://bit.ly/EvoXt)

## Why a cheap Windows VPS is cheap

Two costs explain almost the entire spread between a $5 Windows VPS and a $54 one.

**Licensing.** IONOS states plainly that Linux carries no licensing fees while Windows does, and Contabo names licensing as a primary difference between its Windows and Linux offerings. The hardware is the same; the Windows licence is the surcharge. This is why an identically specced plan costs more with Windows selected, and why the very cheapest Windows tiers tend to be small in RAM rather than slow in CPU.

**Management.** Contabo describes its own Windows VPS product as unmanaged. Liquid Web's RDP plans, at $54 and $71 a month, bundle a Server Secure package, DDoS protection, integrated firewalls, automatic backups, three tiers of management support and a 59-second response claim on calls and chats. The tenfold price gap between €5.50 and $54 buys technicians and security tooling, not faster silicon. Every euro below that line is work you do yourself: patching, firewall rules, backups you verify, and recovery when something breaks at an inconvenient hour.

Neither model is wrong. Pick managed if downtime costs more than the subscription. Pick unmanaged if you can administer Windows Server without looking things up.

## Three billing models, three different years

This is where cheap Windows VPS comparisons usually go wrong. The advertised number and the annual cost are different quantities.

**Contabo: €5.50 for the first 24 months.** The plan listing labels every price that way. Contabo does not publish what happens after the 24 months in that listing, so build your budget assuming the rate rises and confirm the renewal figure before you commit two years. The same listing shows two storage figures on most plans, for example 200 GB SSD / 100 GB NVMe on CLOUD VPS 6. You get one of those, depending on which storage type you pick, not both.

**IONOS: $16 for 3 months with a 1-year term.** The standard price for Windows M+ is $25 a month. IONOS shows "Save $27" next to the offer, and $27 is exactly 3 × ($25 − $16), which confirms that the discount applies to three invoices and the remaining nine are billed at $25.

> IONOS Windows M+ first year: 3 × $16 + 9 × $25 = $273, an average of $22.75 a month. The $16 headline understates the year by roughly 42%.

**OVHcloud: from US$8.50 ex. GST per month.** The "ex." matters if you are comparing against tax-inclusive prices, and the tax is added on top. OVHcloud also footnotes its unlimited traffic as excluding its Asia-Pacific datacentres, so a cheap Singapore-facing deployment does not get the same deal as a European one. One more exclusion buried in the fine print: OVHcloud's Local Zones do not support Windows at all, along with preinstalled apps, additional storage, monitoring, Additional IP, Load Balancer and managed databases. If you pick a Local Zone for latency, you are picking Linux.

Put the three on one line and the ranking changes. Contabo is the lowest sticker price in this set. IONOS's first year at $273 works out more expensive than twelve months of OVHcloud VPS-2 at $8.50, even before tax.

## What a cheap Windows plan can actually run

HostAdvice's October 2026 sizing guidance is a reasonable sanity check on how much machine you need: 1–2 GB RAM with one core handles 5–10 lightweight sites, 4–8 GB with 2–4 cores handles 20–50 depending on what each site consumes, and 8 GB or more with multiple cores supports 50+ with caching and load balancing on top.

The same page makes a structural point worth repeating here. A VPS is one physical server partitioned into virtual machines. If that physical host fails, your instance goes with it. Cloud hosting spreads across multiple servers and survives a node failure; a $6 VPS does not. Nothing in the cheap tier buys redundancy, and no provider at this price claims otherwise.

HostAdvice also lists who should not buy a VPS at all: complete beginners still learning the basics, people whose budget genuinely cannot stretch, anyone without the technical ability to administer a server, and non-critical low-traffic sites that a shared plan would serve. If you are running one small Windows utility for yourself, that warning is worth a second's thought before you take on patching duty.

## How the four options compare on verified numbers

| Provider | Cheapest verified Windows plan | Specs | Billing caveat |
| --- | --- | --- | --- |
| Evoxt | VM-0.5, $2.99/mo | 1 vCore, 512 MB RAM, 5 GB storage | Smallest tier is below a comfortable desktop session |
| Contabo | CLOUD VPS 4, €5.50/mo | 4 vCPU, 8 GB RAM, 100 GB SSD, 1 snapshot, 200 Mbit/s | Rate is "for the first 24 months"; later price not listed |
| OVHcloud | VPS-2, US$8.50/mo | 4 vCores, 8 GB RAM, 75 GB NVMe, daily backup of previous 24 hours | Quoted ex. GST; unlimited traffic excludes Asia-Pacific datacentres |
| IONOS | Windows M+, $16/mo | 2 vCores, 4 GB RAM, 120 GB NVMe | $16 covers 3 months on a 1-year term; standard rate $25 |
| Liquid Web | General RDP VPS, $54/mo | KVM on AMD EPYC, RAID-protected SSD and NVMe, managed support | Managed pricing; backups, security package and 24/7 support included |

€5.50 is the lowest monthly figure in this table on a pure currency basis, and it buys 8 GB of RAM against Evoxt's 512 MB. It also locks in a 24-month term at a promotional rate whose successor price is not published. That trade, more RAM now against a longer commitment at an unknown renewal, is the real decision hiding behind the word "cheapest".

## Pick by what you're actually running

**One person, remote desktop, a browser and Office.** VM-1 at $5.99 is the floor, VM-2 at $11.99 is comfortable. Below 2 GB, Windows itself eats most of the budget before your applications start.

**Trading bots, scrapers, automation that must stay awake.** VM-2 or VM-4, and pick the datacentre by proximity to the exchange or target site rather than by price. A 200 ms round trip feels sluggish on any hardware. Also check the transfer allowance: bots that poll frequently can push past a small monthly quota, and extra transfer on the premium networks costs $12 to $24 per TB.

**SQL Server, ERP, anything with a database on the same box.** VM-4 at $23.99 gives 4 vCores and 8 GB, which is the realistic minimum, and you should confirm the storage type rather than assume it. Where a provider lists both SSD and NVMe figures for one plan, the smaller number is usually the NVMe allocation.

**Several client sites on one machine.** Count IP addresses first. Evoxt charges $3 a month per extra IP, which is cheap, but a shared IP with SNI will not satisfy clients who want their own. Confirm the backup schedule too: weekly offsite is fine for a staging box and thin for live customer sites.

**Windows-only software you cannot replace.** This is the case where paying the Windows premium makes sense at all. If the application runs on Linux, the same money buys noticeably more machine.

## Three things to confirm before you pay

1. **Is the Windows licence inside the monthly price?** Evoxt lists Windows RDP among its operating system options, but confirm at checkout that the figure you saw is the figure you pay with Windows selected, not a Linux base price with a licence added afterwards.
2. **What does the plan cost after the promotional period?** Contabo's listing stops at "first 24 months" and IONOS's at three months. IONOS publishes a $25 standard rate; Contabo does not publish a renewal figure in the plan listing, so ask before committing.
3. **Can you change operating system later?** IONOS is explicit that ordering a Windows VPS locks you out of switching: to move to Linux you place a new order, and if you want the freedom to swap you need a Cloud Server plan instead. Check the equivalent rule wherever you buy, because it decides whether a wrong guess costs you a migration.

If the answer to all three is acceptable, the entry cost really is as low as $2.99, and the useful question becomes how much RAM you want above it.

👉 [Start with Evoxt's VM-1 or compare the full plan list](https://bit.ly/EvoXt)
