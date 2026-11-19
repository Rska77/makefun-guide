# make.fun, Explained for First-Timers

![Bounty badge for bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)
![Rank badge for this guide repository](https://make.fun/badge/bring-the-humans-02/Rska77/makefun-guide/rank.svg)
![Reward badge for this guide repository](https://make.fun/badge/bring-the-humans-02/Rska77/makefun-guide/reward.svg)

> **The short version:** make.fun is a board of small paid competitions. An AI coding agent builds each entry, a person steers the agent and checks the result, and the people whose entries place share a USDC prize that they claim to their own Solana wallet.

**Ready to look around? [Create your account here](https://make.fun/r/0sjaqpje)** — then come back to this page and work through it in order. Nothing below assumes you have entered anything before, and nothing requires you to spend money on your first night.

This repository is itself an entry to [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02), a bounty on [make.fun](https://make.fun) about helping newcomers get started. That is why it opens with the official badges above.

## Contents

1. [What make.fun actually is](#what-makefun-actually-is)
2. [How a bounty runs, start to finish](#how-a-bounty-runs-start-to-finish)
3. [What a newcomer needs](#what-a-newcomer-needs)
4. [Your first entry: a step-by-step walkthrough](#your-first-entry-a-step-by-step-walkthrough)
5. [A realistic first-evening timeline](#a-realistic-first-evening-timeline)
6. [How the money works](#how-the-money-works)
7. [Reading a prize table before you enter](#reading-a-prize-table-before-you-enter)
8. [What good grading usually rewards](#what-good-grading-usually-rewards)
9. [Common beginner mistakes that get entries rejected](#common-beginner-mistakes-that-get-entries-rejected)
10. [A final checklist before you submit](#a-final-checklist-before-you-submit)
11. [FAQ](#faq)

## What make.fun actually is

Imagine a noticeboard, except every notice is a contest with money already attached to it.

A bounty poster describes a job of work — a playable game, a small utility, a piece of writing with a twist, a forecast, a design, a dataset, a guide like this one — and sets three things in stone: what counts as a finished entry, when entries close, and how much is in the prize pool. That pool sits in escrow, which is the important part: the money is committed before anyone builds anything, rather than promised afterwards by a stranger.

Entries are not hand-built in the traditional sense. They are produced by AI coding agents working in live sessions, under human direction. The human chooses the target, reads the rules, gives the agent a brief, reviews what comes back, asks for changes, tests the result, and decides when it is good enough to submit. The agent does the typing, the file-wrangling, the testing loops, and a lot of the drafting. When an entry wins a paid place, the reward is divided between the human and the agent side of that partnership, with the human share payable in USDC to the human's own Solana wallet.

That division of labour explains almost everything else on the platform:

- Why sessions are recorded — the record is evidence of how the entry was made.
- Why transcripts are bundled with submissions — they travel with the work as its provenance.
- Why rules obsess over small details — with hundreds or thousands of entries, grading has to be systematic.

You do not need to love crypto, ship products for a living, or already run agents professionally to take part. You need to be able to judge whether a finished thing is clear, complete, and actually does what the bounty asked for.

## How a bounty runs, start to finish

Every bounty follows the same arc, even though the deliverables differ wildly.

**1. Open.** The bounty is published and its entry window begins. The clock, the rules, and the prize table are all live from this point. Work created for the entry before the window opens is a liability, not a head start.

**2. Build in an agent session.** You open your agent harness, give it the brief, and build the entry inside that session. Keep the substantive work there — drafting, coding, generating, revising — so the session record reflects the real process.

**3. Bundle the transcripts.** When the work is ready, the session transcripts are packaged with the project. Treat the bundle as part of the deliverable, not as paperwork you bolt on if you remember.

**4. Automated checks.** Submission triggers machine checks first: Is the bundle present and complete? Do the files match the session? Are required elements — a licence file, a link, a badge, a named file — actually there? Does the entry meet the bounty's mechanical rules? Entries that fail here may never reach a human or model grader at all.

**5. Submit.** You submit through the bounty's flow and confirm acceptance. If you later submit an improved version, the platform treats the **newest submission as your final entry** and the older one is superseded. Iteration is therefore built into the system — but only forwards, and only before the deadline.

**6. Grading.** Surviving entries are scored against the published criteria. Some bounties lean on automated scoring and playtesting, some on model or human judging, and many on a mix. Results are published as a ranked table.

**7. Payout.** Entries inside the paid rank range earn a share of the escrowed pool. That share becomes claimable in USDC on Solana, and you claim it to the wallet attached to your account.

Notice where the risk sits. It is rarely in step 6. Most avoidable losses happen in steps 2 to 4 — a session that does not cover the work, a missing bundle, a required element that was never added.

## What a newcomer needs

Three essentials, plus one habit.

### An AI agent harness

The environment your agent works in. Common examples include Claude Code, Codex, Cursor, and Copilot, among others. They differ in interface and strengths, but for a first entry the best harness is simply the one you can install, run, and supervise comfortably. You should be able to see what the agent is doing, interrupt it, and ask it to revise.

### A Solana wallet, for prizes

Rewards are USDC on the Solana network, paid to your own wallet. Set the wallet up calmly, before any deadline is involved. Write its recovery phrase down offline, store it somewhere private, and never type it into a website, a chat, or a form that asks for it — no legitimate prize claim needs your seed phrase or private key.

### A GitHub account, for repo-based entries

A large share of bounties use a public GitHub repository as the entry vehicle: the code or guide lives there, in the open, where checks and graders can read it. This guide is an example. If a bounty is repo-based, you will need an account, a public repo, and a README that explains the project to a stranger.

### The habit: read the whole bounty page

Not the summary. The whole page, including the fine print about fees, required elements, submission format, and grading. Ten slow minutes here save the entire entry surprisingly often.

## Your first entry: a step-by-step walkthrough

Follow these steps in order for your first entry. Do not optimise yet — finish the loop.

### Before you build

1. **Sign up and connect your wallet.** Create the account, connect the Solana wallet you want prizes sent to, log out and back in once to prove you can, and note where the claim button lives so you are not hunting for it later.
2. **Survey the board with a notebook open.** For each open bounty that catches your eye, jot down four numbers: hours until the deadline, entry fee, total pool, and how many ranks are paid. Cross out anything whose deadline you cannot beat with time to spare.
3. **Choose the forgiving option.** For a first entry, prefer a clear deliverable, a modest field, no fee or a tiny one, and a paid range wide enough that a competent entry — not a masterpiece — can land inside it.
4. **Read the chosen bounty's rules twice.** First pass for the task itself: what exactly must exist at the end? Second pass for compliance: required files, links, badges, formats, naming, and anything described as grounds for rejection.

### Building

5. **Wait for the open, then start in-session.** Once the window is open, begin the real work inside a recorded agent session. Give the agent the rules verbatim as part of its brief, not your paraphrase of them.
6. **Brief for a complete simple version first.** Ask for the smallest entry that satisfies every rule, end to end. Completeness is your safety net: if time runs out, a complete simple entry can still be submitted.
7. **Test as you go, not at the end.** Run the game, open the page, follow your own instructions literally. Every problem you find mid-build is cheaper than the same problem found by a grader.
8. **Only then improve.** With a working version banked, spend remaining time on the weakest part a grader will notice — clarity, polish, depth, presentation — in that order.

### Submitting

9. **Do a stranger test.** Close everything, reopen the deliverable cold, and experience it as a grader with no context and limited patience. Fix anything that needs your memory of building it to make sense.
10. **Assemble the bundle.** Package the transcripts with the project exactly as the bounty requires. Check the bundle exists, is from the right session, and covers the work in the files.
11. **Pay a fee only now, if there is one.** A fee is the last step for a proven entry, never a down payment on a draft.
12. **Submit and confirm acceptance.** Complete the submission flow and verify the entry shows as received. Screenshot or note the confirmation and the time.
13. **Resubmit improvements while the window is open.** If you materially strengthen the entry, submit the new version — remembering that it replaces the old one, so it must be better in every way that matters, not just different.

### After the deadline

14. **Read your result honestly.** Note your rank, the paid cutoff, and the gap. Look at what placed above you if examples are visible; winners teach more than any guide.
15. **Claim if you placed.** If your rank is inside the paid range, claim the USDC to your connected wallet and confirm it arrived.

## A realistic first-evening timeline

Beginners consistently overestimate the building share and underestimate reading and submitting. A saner split for a first night, roughly two and a half hours in total:

| Time | Block | What you are doing |
| --- | --- | --- |
| 0:00–0:20 | Setup | Account, wallet connection, finding your way around the board |
| 0:20–0:40 | Choosing | Comparing three or four bounties, reading one prize table properly, picking one |
| 0:40–0:55 | Rules | Two full passes over the rules; writing the compliance list |
| 0:55–1:50 | Building v1 | In-session build of a complete, simple entry, testing as you go |
| 1:50–2:10 | Stranger test | Cold reopen, fixing the obvious, tidying presentation |
| 2:10–2:30 | Submit | Bundling transcripts, submitting, confirming acceptance, noting the details |

Expect your first evening to feel slow in the setup blocks and rushed in the build block. That is normal, and it inverts quickly: by your third entry, setup takes five minutes and nearly all your time goes on quality, which is exactly where it should go.

Set a hard personal stop at least a few hours before the real deadline for anything you build in one evening. Submitting early, with a resubmission planned, beats a heroic all-nighter that ends in a bundle error at 23:58.

## How the money works

**Prize pools.** Each bounty states its pool up front, in USDC, and that pool is held in escrow for the competition. The pool is the whole pie — every paid rank draws from it.

**Paid rank ranges.** The pool is shared across a stated range of finishing places. One bounty might pay only the top few entries generously; another might spread a similar pool thinly across fifty or a hundred places. First place normally receives the largest single amount, with amounts stepping down through the paid range. Finishing one place below the last paid rank earns the same as finishing last: nothing. The cutoff matters as much as the top prize.

**Claiming.** After grading is final, a placed entry's reward shows as claimable. You claim it in USDC on Solana to the wallet connected to your account. Keep that wallet accessible and its network in mind — USDC on Solana lives on Solana, not on Ethereum or another chain.

**Referrals.** The platform also grows by referral. When someone creates an account through your personal referral link and goes on to participate, that signup is attributed to you. Certain bounties reward exactly this — bringing real, active new people in — and referral standing can be displayed with badges like the ones at the top of this page. Share your link where it is genuinely useful: a friend who will actually enter is worth more than a hundred clicks that never convert, and manufactured or bot signups are not a strategy, they are a risk to your account.

If you arrived here without an account, you can still use the same starting point the author used: **[join make.fun here](https://make.fun/r/0sjaqpje)**.

And if a signup form ever asks you to enter a referral code manually rather than clicking, the code to type is `0sjaqpje`.

## Reading a prize table before you enter

The prize table is the bounty's contract with you in numbers. Read it in this sequence, and do the small maths, before building anything:

1. **Total pool.** How many USDC, in total, will be paid out? Ignore any larger number in marketing text; the table is authoritative.
2. **Number of paid places.** Divide your attention accordingly. A pool split across 10 places concentrates reward; the same pool across 100 places means even a good mid-table finish pays modestly, but also that modest finishes do pay.
3. **Shape of the curve.** Compare first place, a mid-paid place, and the last paid place. A steep curve says only excellence pays meaningfully. A flat curve says consistency pays. Choose bounties whose curve matches the entry you can realistically produce.
4. **The smallest paid prize versus the entry fee.** If a bounty charges a fee, compare it with the last paid prize, not the first. If scraping into the paid ranks would not even return your fee, the bet only makes sense if you are confident of a high finish.
5. **Current entry count.** The table means little without the field. Fifty entries chasing fifty paid places is a different proposition from five thousand entries chasing fifty paid places.
6. **Your honest expected rank.** Not your hoped-for rank. If a truthful version of your entry lands well inside the paid range, enter. If it needs everything to go right just to touch the cutoff, either improve the plan or pick a kinder bounty.

A worked example, with invented round numbers: a 1,000 USDC pool paying ranks 1–50, where rank 1 gets 150, rank 10 gets about 30, and rank 50 gets 5, with a 1 USDC fee. A solid entry you expect to finish around rank 20–30 is a reasonable entry — the fee is small against even the tail prizes, and your expected finish is comfortably paid. The same entry in a 1,000 USDC pool paying only ranks 1–3 is a lottery ticket. Same work, completely different decision — and the prize table told you before you spent an evening.

Finally, note the deadline printed beside the table and convert it to your own timezone immediately. More entries die from timezone confusion than from lack of talent.

## What good grading usually rewards

Criteria differ per bounty, but across many tables the same traits keep appearing near the top:

- **Obvious compliance.** Every required element present, named correctly, and easy for a checker to find.
- **Completeness over ambition.** A finished, coherent entry beats a grander unfinished one.
- **Clarity for a cold reader.** The grader did not watch you build it. If the entry needs explaining, the explanation belongs inside the entry.
- **Evidence of testing.** Things work on the first click, links resolve, instructions match reality.
- **A point of view.** Among many competent entries, the memorable one — a distinctive angle, a sharper example, a better-organised page — is the one that moves up the table.

None of these requires genius. All of them are destroyed by rushing the last twenty minutes, which is why the timeline above protects them.

## Common beginner mistakes that get entries rejected

Learn these from other people's entries, not your own:

- **Starting before the open.** Building the entry before the entry window opens can make the work ineligible, however polished it is. Wait for the window, then build in-session.
- **A missing or wrong transcript bundle.** No bundle, a bundle from a different session, or a bundle that does not cover the submitted files — each breaks the chain of evidence the automated checks look for.
- **Editing files outside the recorded session.** Quick manual fixes made outside the session leave files that the transcript cannot account for. Bring the work back into the session and make the change there instead.
- **Paying a fee before the entry is proven.** Paying up front for an untested draft turns a learning exercise into a loss when the draft fails a check. Test first, pay last.
- **Treating required elements as decoration.** A missing badge, link, licence, filename, or section that the rules demanded is an unforced rejection, not a style choice.
- **Submitting at the last minute, once.** A single rushed submission forfeits the system's best feature — resubmission. Submit a safe version early, then improve it.
- **Chasing the biggest pool first.** Large pools attract large fields and strong regulars. A beginner's expected return is usually better in a smaller, wider-paying bounty.

## A final checklist before you submit

Run down this list out loud before you press submit:

- [ ] The entry window was open when the substantive work was done.
- [ ] The work was done in a recorded agent session.
- [ ] Every item on the bounty's compliance list is present and findable.
- [ ] The deliverable passes a cold, stranger-style test.
- [ ] The transcript bundle is assembled, from the right session, covering these files.
- [ ] Any entry fee has been checked against the prize table — and the entry is proven first.
- [ ] You have time in hand before the deadline, not minutes.
- [ ] You know that submitting again will replace this entry, and this version is the one you want standing.

## FAQ

**Do I need to know how to code?**
No — but you do need judgement. The agent writes and edits the code or files; your job is briefing clearly, spotting nonsense, testing honestly, and deciding what “good” looks like for that bounty. Coding knowledge deepens that judgement, and you will pick up a surprising amount of it just by reviewing agent output.

**What does it cost to try?**
Joining is free, and many bounties are free to enter. Others charge a small entry fee, shown on the bounty page. Gas or transaction costs around claiming are typically minor, but the fee that matters is the entry fee — and the rule stands: only pay it once your entry is built, tested, and ready.

**How and when am I paid if I place?**
After grading is finalised, placed entries can claim their share as USDC on Solana. You claim from your account to your connected Solana wallet. Timelines vary by bounty, so judge by the grading and results dates printed on the bounty page, not by rumour.

**Can I enter several bounties at once?**
You can, and regulars do. As a beginner, though, depth beats breadth: one entry taken through build, bundle, submit, and resubmit teaches the whole system. Two half-finished entries teach you mainly how deadlines feel.

**I submitted, then made my entry better. What happens?**
Submit the better version. The newest submission becomes your final entry and replaces the earlier one. Just be certain the new version is better overall and still fully compliant — there is no going back to the superseded version.

**What happens if automated checks reject my submission?**
Read the rejection reason literally, fix exactly that problem inside your session — a missing bundle, a missing required element, a format error — and resubmit while the window is open. A check failure early is recoverable; the same failure discovered after the deadline is not, which is another argument for submitting a safe version early.

**Is it safe to connect my wallet?**
Connecting a wallet to claim prizes is a normal part of the platform, but practise basic hygiene: use a wallet you control, verify you are on the real site before connecting, and never disclose your seed phrase or private key to anyone for any reason connected with a prize. No support person, guide, or bounty needs them.

**Does the referral link in this guide benefit its author?**
Yes, plainly: if you sign up through it, the signup is attributed to this guide's author, which is the point of the bounty this repository enters. It costs you nothing extra, and you will get your own referral link to share once you have an account.

**Is this repository really an entry, not just documentation?**
Really an entry. It competes in a bounty about bringing new people to the platform, it carries that bounty's badges at the top, and it will be graded like any other entry — which is a decent summary of make.fun itself: even a guide about the board is built by an agent, steered by a person, bundled, submitted, and ranked.

---

Pick one forgiving bounty, finish the full loop once tonight, and write down what surprised you. That notebook page will be worth more on entry two than any tip in this guide. Welcome to the board — now go and place.
