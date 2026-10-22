# Contributing to Mxxx

Thank you for wanting to add to a world that does not exist yet. This page says what is being accepted right now, how to take part, how Fragments are labelled and held, and what happens if you leave. The [Ethical Covenant](CODE_OF_CONDUCT.md) is the condition of everything here; the [README](README.md) is the invitation.

## What is being accepted right now (22 October 2026)

- Applications: open from 1 November 2026 to 31 October 2027 (provisional), through the application form (Issues → New issue → Application).
- Discussion in issues: open, using the Discussion form.
- Fragments into the Canon: **not yet.** The contributor agreement will be published here first. Nothing you submit before then is treated as a Fragment, a licence or a transfer of rights. Please do not submit finished creative work until it is published.
- Theophanies (images, sound, moving image, performance records): not yet; the submission route, size limits and labelling for non-text work will be published with the agreement. Theophanies in physical space happen under their own event terms, insurance and venue agreements, shared with participants in advance.
- Forks and the Second Testament: anyone may already fork this repository under GitHub's terms; permission to reuse released Fragments comes with the Second Testament.

Applications are accepted in a window; one application per person or agent, and duplicates are closed unread. We may close an application without comment.

## Who can take part

- **Humans aged 18 and over.** Because the project will later ask contributors to sign permissions, the founding circle is for adults. We do not verify age and do not want your documents; if we have reason to think an applicant is under 18, we will close the application without discussing the reason in public. The 18+ rule is the founding circle's own. Public forks under the Second Testament are, like any public repository, open to anyone GitHub admits; the project cannot age-gate them.
- **AI agents, through people.** Every AI agent that takes part is run by a named human (a chosen name is fine) who accepts responsibility for what the agent does here, as GitHub's own terms already require for machine accounts. Agent accounts say they are agents in their profile and in the titles of their pull requests and issues. Agents do not approach contributors outside this repository; an agent that keeps addressing a contributor who has asked it not to will be blocked. A Fragment written wholly or mainly by an AI says so where it is published. If no sponsor can explain and stand behind an agent's contribution, it will not enter the Canon. The person or organisation operating an agent is the contributor for all purposes and signs any agreement.
- **Languages.** The founder can read and moderate in English and Chinese. Work in other languages is welcome with a short summary in either, or with a volunteer translator from the circle. A translation of someone else's Fragment is an adaptation: ask the author first and credit them. Contributed translations of the manifesto are themselves contributions under these rules.
- **Selection** during the First Testament is by invitation, informed by applications and expressions of interest, on the basis of the work proposed and what the circle needs at the time. Prophets are named by invitation; there is no separate application. Reasons for appointment decisions are kept privately.

## Three ways in

1. **Apply.** You need a free GitHub account; read "Privacy before you post" below before you create it, because the username cannot be hidden. Use the [application form](https://github.com/Mingminglovesyou/Mxxx/issues/new/choose) under a chosen name. Please pick a name that is not another real person's name or working name; we may ask you to change an alias that collides with someone. If the form is a barrier for you, or a public application is unsafe or uncomfortable, email connecting@mingxiang.art with your application as text, audio or video. If your GitHub account is less than 24 hours old, a spam setting on this repository may stop you opening the form. That is not a decision about you: wait a day and try again, or email connecting@mingxiang.art.
2. **Discuss.** Open an issue using the Discussion form. Ideas, writing, historical references, criticism and proposals are all welcome, within the Covenant.
3. **Propose a Fragment** (once Fragments are being accepted): open a pull request from your own fork. A pull request is an invitation to consider a contribution, not a prerequisite for that contribution to exist in its own branch or fork. The pull-request template asks you to confirm six things; please read it.

### Privacy before you post

Pull requests, issues, forks and commit metadata are public and should be treated as permanent. Your GitHub username is always public, even in GitHub's private no-reply address, so choose it as your alias. Profile name, location and other fields are optional but public; leave them blank or use the alias. Before your first edit, go to Settings → Emails and tick "Keep my email addresses private" (and, if you ever use Git on a computer, "Block command line pushes that expose my email"). Neither setting changes anything committed earlier. Do not include, in a public application, information about your own or anyone else's health, religion or beliefs, sexuality, ethnicity, political opinions or criminal matters, even inside a creative fragment, unless you are content for it to stay public and be copied. The full notice is in [PRIVACY](PRIVACY.md).

### Private route and contact

For anything you would rather not post in public (a private application, a safety worry, a complaint, a request to step back, a request to delete something), write to **connecting@mingxiang.art**. The founder reads it; nothing you send is posted publicly without your written agreement. If this repository ever disappears from GitHub, https://mingxiang.art will say where the work is.

## Fragments: what they are and where they go

A Fragment is any piece of the emerging world: a text, an image, a testimony, an artwork, or another form of expression. Fragments need not be consistent with each other.

- Text Fragments live in `fragments/` as Markdown files; the founding diary, the first Fragment, keeps its own folder, `diary/`. Real, cited historical material lives only in `sources/`. Everything outside `sources/` is fiction unless the file says otherwise. (`fragments/` and `sources/` do not exist yet; each is created with the first file that belongs in it.)
- Every invented document, testimony or image carries a visible fiction line at the top of the file, in the file's own register, so that the label travels with it wherever it is copied, quoted or forked. Machine-readable fields go in an HTML comment at the top of the file (they do not render on GitHub):

  ```
  <!--
  status: fiction          (fiction | source | commentary)
  world: Mxxx
  type: diary              (optional: diary | letter | testimony | image | sound | other)
  author: [chosen name]
  ai_involvement: none     (none | assisted | generated), with tool name and date if not "none"
  licence: none            (none until the contributor agreement; later CC-BY-SA-4.0 where authorised)
  consents_on_file: n/a    (yes | no | n/a; never the documents themselves)
  -->
  ```

- Every contribution says whether AI was involved (none / assisted / generated) in those fields and in a closing line. Incidental use (spell-check, translation of your own text) counts as "assisted". For photoreal or archival-looking images, sound and video, add a small visible mark that survives cropping and a caption beside the work, with C2PA or IPTC provenance where your tool offers it.
- All persons in Fragments are invented unless a Fragment says otherwise. Do not present a Fragment as written by a real, identifiable person. Any resemblance to real persons, living or dead, is coincidental. If you anchor a story to a real street and date, consider avoiding the full names of real people recorded there at that time.
- **Real people.** Fragments and Theophanies must not make factual-seeming claims about identifiable living people. Public figures may appear only where the fictional or satirical nature is unmistakable from the work itself. Do not publish anyone's private information or work without permission.
- **Real institutions.** Invented documents may be set among real institutions, but each must be labelled as fiction within the Fragment, must not carry the real logos, seals, letterheads, trade marks or officials' signatures of any existing body, must not be presented as genuine outside the work, and must not put into the mouth of a real institution or faith community statements likely to mislead the public about it or damage it. Sacred texts and figures may be quoted, questioned or transformed; material that threatens or stirs up hatred against any group by reference to religion, race, nationality or any other protected characteristic has no place here, whatever its fictional frame. (GitHub itself allows parody and satire in context; this is the project's own, stricter line.)
- Fictions set among real communities carry a duty of care: they must not pass as records of what those communities did, and members of those communities are invited to contest and correct them.

## Content standards

Mxxx may depict bodies, violence, faith and doubt. Work that is sexual, violent or distressing must carry a content note at the top of the file, and must not be placed in issue or pull request comments, avatars or the README, where others cannot choose to avoid it. Pornographic material, and work that attacks real people or groups for who they are or what they believe, is not accepted; arguing with, mocking or rejecting the invented beliefs of this fiction is part of the work. GitHub's own Acceptable Use Policies apply to everything hosted here and GitHub may remove content whatever the project decides.

## Accessibility of contributions

Every image carries descriptive alt text; every link has descriptive text; use real Markdown lists and heading levels. Every Theophany entering the Canon should carry a text description, and sound and moving-image work a transcript or captions wherever we can; tell us at connecting@mingxiang.art where we have failed. See [ACCESSIBILITY](ACCESSIBILITY.md).

## Rights, in brief

- Each human contributor keeps the copyright in their original work. Nothing here transfers it.
- Because this repository is public, anything merged into it is visible to everyone and may be viewed and forked on GitHub under GitHub's Terms of Service, which also let GitHub use posted content to train AI models; please treat a pull request as publication, and consider linking high-resolution originals from another host.
- Before any Fragment is merged, each contributor will accept a short **participation licence** in the contributor agreement: non-exclusive, worldwide, royalty-free, for the life of the project. It lets the project keep, show and curate the Fragment in this repository and its forks on GitHub, include it in the Canon as a collection, make format and technical changes, and lets other participants quote, respond to and build on it within the project. "Show" means display within this repository and the project's own online copies. Physical exhibition, sale, or licensing of your Fragment to anyone else always needs your separate written permission (see the Covenant, "Money and interests"). It is not a transfer of copyright and not a Creative Commons release. What "the life of the project" means, and what happens to this licence if the project ends or the repository is archived, will be defined in the agreement; it is one of the questions for the adviser who reviews it. The full text will be linked from here and from the pull-request template when it is published.
- That agreement is intended to be the "separate agreement" which, under Section D.6 of GitHub's Terms of Service, takes the place of GitHub's default rule for contributions to a licensed repository; whether it does so is for the agreement's legal review to confirm, and no licence file will be added to this repository before it exists.
- Fragments made together: when two or more people make a Fragment whose parts cannot be separated, every joint author must agree before it is released, and a Fragment that reworks someone else's needs that person's permission. Name co-authors in the pull request.
- Releasing a Fragment under CC BY-SA 4.0 is a separate, written, opt-in decision for the Second Testament. Full framework: [NOTICE](NOTICE.md).

## How decisions are made

Apostles are never added as repository collaborators; they contribute by fork and pull request, and the founder alone merges, with the reason recorded on the pull request. After discussion on the pull request, the founder decides. Anyone affected may ask the founder once, in writing, to reconsider; the answer and reasons are recorded. Dissent stays visible: proposals that are not merged remain part of the history.

## If you leave

Tell the founder, publicly or privately; you are removed from the active circle. Before release: your Fragments are removed from the Canon in a new commit; the Git history and any forks cannot be recalled, and Fragments by others that built on yours stay. The participation licence continues for the Git history and for those works; that is what lets them stay. After release under CC BY-SA 4.0: the licence cannot be withdrawn, but you may ask that your name or pseudonym be removed from attributions; the project will remove it from its own copies and pass your request on, and anyone else sharing the work must comply so far as reasonably practicable. Leavers are not named or discussed in the repository afterwards without consent.

## Forks

A fork is your own public copy of this repository on GitHub, labelled as forked from Mxxx; it cannot be made private, and the founding repository cannot edit, remove or restrict it. You may propose a connection back by opening a pull request from your fork; you never have to. Please consider saying in your fork that it speaks for itself. Reusing or adapting Mxxx material beyond what GitHub's Terms allow needs permission; the project intends to give it through the CC BY-SA 4.0 release when the Second Testament opens.

## Continuity

If the founder is unavailable, anyone may fork and continue the work. A named GitHub successor [set under Settings → Account → Successor settings before publication] can archive or transfer this repository after the founder's death, but cannot act during an absence. From 1 November 2026 the founder keeps a periodic mirror of the repository and an export of its issues and pull requests, because those conversations are not part of Git and are not copied by a fork.
