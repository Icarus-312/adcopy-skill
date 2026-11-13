---
name: adcopy
description: Write direct-response ad copy for ONE contractor/trade avatar using a 4-part framework (Avatar callout + pain, deeper pain points, Solution, CTA with the why then the CTA again), with bam-bam-bam transitions between paragraphs. Use whenever the user says "/adcopy", "/adcopy <industry>", "write ads for <industry>", "make ad copy for <industry>", or wants more ads in the HVAC-style format. Takes the industry as input and returns 3 variants in chat, all on the same avatar.
---

# /adcopy — 4-part ad framework

Input: ONE avatar (e.g. `/adcopy roofing`). If none given, ask exactly this and nothing else: "Which one avatar is this for? (e.g. roofing owners doing $500k+)". Never ask for several avatars or offer a multi-niche batch. If several are given, ask which one the funnel targets.

Defaults (do not ask unless the user overrides):
- Offer: contractor credit solution. We reverse engineer what banks look for, make the owner the "perfect borrower", and use our existing banking relationships so it is hands off.
- Avatar floor: owner doing over $500k revenue, good score, good revenue, banks still say no or make it hard.
- CTA: "DM me [KEYWORD] and I'll send my free guide."
- Proof line: SKIP by default. Only include one if the user supplies a real client result. Never invent numbers, approvals or timelines.

## Rule 1: one avatar, across the entire funnel

From reviewer feedback on a multi-niche batch: "one avatar is better. You stick to avatar across the entire funnel."

- One run = one avatar. All 3 variants call out the exact same owner, with the same avatar line word for word ("If you're a roofing owner doing over $500k..."). Variants change the hook angle, never the avatar.
- Never spread a batch across several niches. If the user asks for multiple niches at once, ask one question: "Which avatar does this client's funnel target?" Then write for that one.
- If the client's landing page or funnel already names an avatar, match it exactly.

## Rule 2: bam bam bam, no pausing

From the same review: "some of the transitions on the paragraphs dont flow. Try to read it excitable like you were reading an ad. Its supposed to go bam bam bam no pausing. So transitions like 'so thats why', so, because, etc."

- Every paragraph after the first opens with a connector that pulls forward from the one before: "And", "But", "So", "Because", "So that's why", "That's exactly why", "And that's where we come in".
- No paragraph starts cold. If you can read the last line of one paragraph and the first line of the next and there is a beat of silence between them, add a connector.
- No ellipses ("...."), no trailing-off sentences, no dead stops. Each line drives into the next.
- Read every draft back in your head as an excited, fast ad read. If it drags anywhere, fix that spot before printing.

## The framework (every ad has all four, in this order)

The format is avatar callout and pain, good pain points, dive deeper into the pain, introduce the solution, then CTA with the why before it. Order and weight matter.

1. **Avatar callout + pain (hook)**: one opening line that names the owner ("If you're a [trade] owner doing over $500k...") and the thing they need funded, plus the bank problem. Avatar and pain together, tied to funding. Get the avatar right: a specific trade owner, not "business owners".
2. **Dive into the pain points**: do not move on. Reiterate the pain from the hook and go deeper. Good score, good revenue, banks still make it hard, it wastes their time. Use the industry's own pains. This section is the longest of the four. Open with "And" or "Because".
3. **Solution**: introduce what we do, opening with a connector ("So that's why...", "And that's where we come in"). The contractor credit solution, reverse engineered bank criteria, perfect borrower, hands off. Fold what they want (fast approval, the specific truck or crew, no more wasted time) into this section as the outcome. No separate goal section.
4. **CTA, with the why first**: open with "So", break down why they should take the action (why DM, why the free guide, why now), then give the CTA: DM me [KEYWORD] for a free guide. Then say the CTA again, same keyword, as the last line.

## Industry adaptation

- Use the trade's own words for what money buys: HVAC = trucks, vans; roofing = trucks, crews, materials float; landscaping = mowers, trailers, trucks; plumbing = vans, equipment; trucking = rigs, trailers. Pick specifics, not "equipment".
- Add a rush angle where it fits (peak season, a big job waiting, crews idle for lack of a truck).
- Keep the $500k+ floor unless the industry clearly needs a different one. Say so if changed.
- Keyword: one short ALL-CAPS word tied to what they want to buy (TRUCK, CREW, RIGS, EQUIPMENT). Different per variant is fine.

## Output

3 variants in chat, same avatar, each with a different hook angle (e.g. trucks/equipment, rush/busy season, bank said no). Each variant must pass the check before printing:
1. Same avatar line as the other two variants.
2. Avatar and pain up top, a pain section that reiterates and goes deeper, then the solution, then the why, then the CTA twice.
3. Every paragraph after the first opens with a connector. No ellipses. Reads bam bam bam out loud.

Print each as finished, paste-ready copy: plain, direct, second person, short paragraphs. Label each variant with its angle and keyword. No preamble, no explanation of the framework, no saving to files.

If a proof line was skipped, end with one line: "Proof line skipped. Give me a real client result and I'll slot it in."

## Reference example (HVAC, transitions fixed)

Paragraph map: 1 = avatar callout + pain, 2 = pain, 3 = solution, 4 = why + CTA twice (a proof paragraph goes before it only with a real client result). Its pain section is still thinner than ideal. New output should dig deeper there and keep the why distinct from the CTA lines.

> If you're an HVAC owner doing over $500k revenue and you need more trucks and vans but the banks are not getting you approved for what you need.
>
> Because you have a good score, you have the revenue, but the banks keep making it hard for you and it's wasting too much of your time.
>
> So that's why we built our contractor credit solution. We have reverse engineered what exactly the banks are looking for to turn you into the perfect borrower, and we have built all the banking relationships to make it a lot easier and hands off for you.
>
> So if you need funding fast, DM me TRUCK and I'll send over my free guide showing you how to get funding fast. DM me TRUCK and I'll send it to you now for free.
