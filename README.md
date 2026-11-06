# Astroceleb website

Static HTML/CSS/JavaScript website for the astrology app shown in the supplied Figma file. The header and footer use the supplied Astroceleb logo (node 26:630). No framework, build step, or payment keys are required to serve these files.

## Preview

From this directory, run `python3 -m http.server 8765` and open `http://localhost:8765/`.

## Pages

- `index.html` — home
- `services.html` — app services and pricing approach
- `about.html` — business and product overview
- `contact.html` — customer support and merchant details
- `terms.html` — terms and conditions
- `privacy.html` — privacy policy
- `refunds.html` — cancellation and refund policy
- `shipping.html` — shipping and delivery policy

## Complete before submitting to Razorpay

1. Add the real registered merchant name, postal address, support email, and phone number to `contact.html` before submitting the site for Razorpay review. The contact page currently contains no direct contact method.
2. Confirm that the public merchant name matches the Razorpay application and the actual app brand. The website uses **Astroceleb** from the supplied logo; other Figma screens contain **AstroTalk** labels, so confirm which brand is correct.
3. Confirm which Figma services are actually live. Remove any unlaunched service from `services.html` and corresponding policy wording. Add real prices or a clear, reachable app listing and checkout where customers can see the exact price before paying.
4. Review `refunds.html` and approve the proposed cancellation windows, support response times, refund processing time, and product return rules against your actual operations.
5. If physical Shopping is live, put the real shipping regions, dispatch and delivery ranges, fees, and tracking method in `shipping.html` and the app checkout. If it is not live, remove the physical-product claims and state that digital services have no shipping.
6. Check `privacy.html` against the production app's actual data collection, providers, account deletion process, retention periods, and child/guardian consent flow.
7. Host the site on a public HTTPS domain and verify that every page, app link, contact method, product listing, and checkout is accessible. This static site does not integrate Razorpay checkout or request live keys.

Razorpay states it may review merchant channels for matching services, displayed prices, refund policy, and contact details. Its merchant terms require return/refund timelines and customer terms to be displayed. See [Razorpay merchant terms](https://razorpay.com/terms/) and [Razorpay's website requirements for international payments](https://razorpay.com/learn/breaking-down-the-requirements-for-accepting-international-payments-through-razorpay/). Final activation remains Razorpay's decision.
