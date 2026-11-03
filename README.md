# buy vps: What to Check Before You Pay, With Real Plan Prices, Renewal Fine Print, and a Full RackNerd Comparison

Most people searching "buy vps" already know what a VPS is. What they actually want is an answer to three questions: what will this really cost me over two or three years, what am I giving up at the cheap end, and what happens if I pick wrong. Those three questions are exactly where cheap VPS offers tend to hide their problems, so this guide walks through them in order, using RackNerd's current KVM VPS specials as the worked example.

RackNerd is a US-based infrastructure provider that has landed on the Inc. 5000 list three years running (it ranked #3,693 nationally in the most recent cycle), and it currently operates 20 datacenter locations across North America, Europe, and Asia. Its VPS specials are unmanaged KVM virtual machines starting at **$21.99 per year** — roughly $1.83 a month — which puts them well below the $4/month entry points you'll see at bigger names like DigitalOcean or IONOS. Cheap, though, only matters if the price stays cheap. We'll get to that.

> **Quick picks**
> - Most people: the **1 GB KVM VPS at $21.99/year** (1 vCPU, 20 GB SSD, 3 TB traffic). It's the plan RackNerd itself marks "Most popular," and it renews at the same price for as long as you keep it.
> - Running AI tooling like Ollama, AnythingLLM, or LibreChat: jump to the **4 GB plan ($59.99/year)**.
> - Want to test before committing yearly: pay monthly instead — monthly billing is available on the standard KVM VPS lineup.
>
> 👉 [Check the current RackNerd VPS specials and order the 1 GB plan](https://bit.ly/RacKnerd)

## The one thing to check before anything else: the renewal price

The renewal price decides your real cost, and it's the number most VPS marketing makes you hunt for.

Here's the pattern to watch out for: plenty of providers advertise a teaser first-term price, then renew at the standard rate — sometimes several times higher. A "$4/month" plan that renews at $12/month costs you $144 in year two, whatever the landing page said.

RackNerd's specials work the other way. The FAQ on its specials page states it directly: "These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service." That means the 1 GB plan is $21.99 in year one and $21.99 in year five. Over three years, the cheapest plan costs $65.97 total — about $22 a year for a KVM machine with a dedicated IPv4 and 3 TB of monthly traffic.

This is the single biggest differentiator in the budget VPS space, and it's the thing to confirm on any provider's page before you enter payment details. If a deal doesn't say "recurring," assume it doesn't renew at that price.

👉 [See all five RackNerd yearly plans with lifetime renewal pricing](https://bit.ly/RacKnerd)

## RackNerd VPS specials: the full lineup

All five current specials are KVM virtualized, run on Intel Xeon hardware with RAID-10 protected SSD storage, and include full root access, one IPv4 address, a 1Gbps port, and RackNerd's ctrl control panel. Every plan is unmanaged: RackNerd keeps the platform running and answers tickets 24/7 (the company cites an average response time under 10 minutes), but server administration is on you.

| Plan | vCPU | SSD | Monthly traffic | Price (billed yearly) | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 | 20 GB | 3 TB | $21.99 | [ Order the 1 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=952) |
| 2 GB KVM VPS | 2 | 35 GB | 5 TB | $35.99 | [ Order the 2 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=953) |
| 4 GB KVM VPS | 3 | 60 GB | 7 TB | $59.99 | [ Order the 4 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=954) |
| 6 GB KVM VPS | 6 | 100 GB | 12 TB | $89.99 | [ Order the 6 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=955) |
| 8 GB KVM VPS | 7 | 150 GB | 20 TB | $119.99 | [ Order the 8 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=956) |

A few things the table doesn't show but should influence your pick:

- **Operating systems**: at order time you choose from CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, or Ubuntu. Custom ISO installs are possible through a support ticket, and the ctrl panel includes an out-of-band HTML5 VNC console if you want to install from your own media later.
- **Other plans exist outside the specials**: the standard KVM VPS lineup starts at $26.99/year for a 512 MB machine (1 vCPU, 30 GB SSD, 500 GB traffic) and scales up to 12 GB RAM / 7 vCPU / 300 GB storage / 6 TB traffic, with monthly, quarterly, semi-annual, and yearly billing. If $21.99 is still more commitment than you want, that 512 MB plan or a monthly term is the entry point.
- **Traffic is the quiet standout**: 3 TB/month on the cheapest plan is generous for this price class. If you're proxying, self-hosting media, or running a busy personal site, compare traffic allowances before comparing CPU cores.

## The fine print: refunds at RackNerd

RackNerd does not offer a money-back guarantee, and this should factor into how you order.

The company's terms of service put it plainly: "Refunds are issued on a case-by-case basis since by default no refunds are provided once payment is received." In practice, that means once a payment clears, getting money back depends on a billing ticket and the specifics — a VPS that won't boot minutes after provisioning is a very different conversation from "I changed my mind" three weeks in. Third-party guides to RackNerd's policy also note that initiating a credit card chargeback triggers a $125–$250 administrative fee and possible account suspension, so disputing a payment through your bank is the worst available option.

Three practical consequences:

1. **Test the network before paying.** RackNerd publishes looking glass and test files for each datacenter. Run a ping and a download test from your own connection to the location you're considering — Los Angeles for Asia-optimized routes, Amsterdam or Dublin for Europe — before you order.
2. **Consider a monthly term first.** The standard KVM VPS lineup supports monthly billing, which is the cheapest way to find out whether the service fits before locking in a yearly special.
3. **Back up before cancelling.** The cancellation request in the client area offers "Immediate" or "End of Billing Period" — and an immediate cancellation terminates the service within 24 hours with data deletion. If you cancel at all, export your data first.

None of this makes RackNerd a bad buy; it makes it a "know what you're buying" purchase, which at $22 a year is a reasonable trade for most people.

## How the specials stack up against better-known names

A quick, link-free reality check against providers you'll see in the same search results:

- **DigitalOcean** lists VPS plans starting at $4/month — about $48/year, versus $21.99 for RackNerd's 1 GB special. DigitalOcean's API, images, and documentation are excellent, and for production app hosting that tooling can be worth the difference. For a single self-hosted box, it's hard to justify paying double.
- **IONOS** advertises VPS hosting from $4/month with unlimited traffic and 24/7 support — competitive pricing, but check whether the advertised rate is a first-term promo before comparing it to a lifetime-recurring price.
- **LightNode** offers hourly-billed VPS from $7.71/month with broad location coverage and Alipay support — a genuinely useful model if you spin machines up and down constantly, and more flexible than RackNerd's fixed terms.
- **GoDaddy** sells managed KVM VPS with automated backups and monitoring. If you want someone else to patch and watch the server, a managed provider is the right category; RackNerd's specials are unmanaged by design.

Where RackNerd wins on paper is recurring price per gigabyte of RAM and traffic. Where it doesn't compete is management: there's no managed tier, no built-in automated backups, and no hand-holding.

## Buying and getting online: what actually happens after checkout

The order flow is short, and knowing it removes the last friction.

1. Pick a plan, then choose a datacenter location and OS at the configuration step. Locations on the official order flow include Los Angeles, San Jose, Seattle, Dallas, Atlanta, Chicago, New York, Ashburn, Amsterdam, France, and Dublin.
2. Complete checkout — RackNerd accepts PayPal, credit cards, cryptocurrency, and wire transfer. Specials are provisioned right after payment.
3. Watch for two emails: an order confirmation, and one titled "KVM VPS Login Information" containing your IP, SSH root credentials, and ctrl panel URL. Most deployments complete within 5–15 minutes.
4. SSH in. On Windows use a client like Bitvise; on macOS or Linux, plain Terminal. If a password paste seems to do nothing, it's working — many SSH clients just don't echo pasted input.
5. Manage the machine in ctrl: reboot, reinstall the OS, open the HTML5 VNC console, set inbound firewall rules, reset the root password, or upgrade the plan.

One quirk worth knowing before it costs you ten confused minutes: **your ctrl panel login is separate from your client area login**. If you can't find the ctrl credentials, log into the client area and open the "View Email Log" section — the KVM VPS Login Information email is stored there.

## Which plan for which workload

The cheapest plan is the right answer more often than upsell pages suggest, but RAM is the real dividing line — especially now that RackNerd ships one-click apps for self-hosting and AI work directly in ctrl.

- **1 GB ($21.99/year)**: a personal website, a small WordPress install (via the AdminBolt, CyberPanel, or CloudPanel one-click), a VPN endpoint, a bot, a lightweight proxy, or a Git server. Fine.
- **2 GB ($35.99/year)**: the same, with headroom — plus n8n or Coolify, which the official FAQ says run comfortably from 2 GB. Docker with Portainer also fits here.
- **4 GB ($59.99/year)**: the minimum for the lighter AI stack — Ollama, AnythingLLM, LibreChat, and Hermes Agent all want at least 4 GB per the official FAQ. This is the sensible floor for anything LLM-adjacent.
- **6 GB ($89.99/year)**: mid-sized self-hosted stacks, busier databases, or several services on one box.
- **8 GB ($119.99/year)**: the floor for OpenClaw, which needs at least 8 GB. Also the pick for larger Ollama models and multi-service AI setups.

The jump from 4 GB to 6 GB is the least dramatic in the lineup price-wise relative to what you get — 6 vCPUs and 100 GB SSD at $89.99 is a strong ratio — but don't buy it speculatively. VPS resources are easy to upgrade later from the ctrl panel; the money you didn't spend is yours to keep.

👉 [Get the 8 GB plan if you're running OpenClaw or a heavier AI stack](https://my.racknerd.com/aff.php?aff=11397&pid=956)

## Quick answers

**Is a yearly VPS special risky if the provider refunds nothing?**
It's a real trade-off, managed by testing first. Use the looking glass tools before ordering, and pick a monthly term on the standard lineup if you want a paid trial before committing $21.99–$119.99.

**Do RackNerd's special prices go up at renewal?**
No. The official FAQ states the specials are lifetime recurring — you renew at the same rate for as long as you keep the service.

**Can I install an OS that isn't on the list?**
Through a support ticket, yes — custom ISO installs are supported, and the ctrl panel's HTML5 VNC console lets you install from your own media.

**Is RackNerd good for beginners?**
Only beginners who are willing to run their own server. Root access means root responsibility; if you want managed backups and monitoring, a managed VPS from a provider like GoDaddy fits better, at a higher price.

## Before you click buy

Match the plan to the workload one more time: a blog or proxy lives happily on the 1 GB at $21.99/year; anything touching local AI models needs the 4 GB at minimum, and OpenClaw requires the 8 GB. Pick the datacenter closest to whoever will actually be typing in the URL, run one last ping through the looking glass, and check that the plan you're ordering says "lifetime recurring" — RackNerd's do, but that habit will save you on every other hosting purchase too. When you're ready, 👉 [compare all RackNerd VPS plans and current pricing in one place](https://bit.ly/RacKnerd), and your machine will be waiting with root credentials in your inbox about ten minutes later.
