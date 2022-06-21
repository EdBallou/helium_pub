# HIPXX: Rescind Redenomination

- Author(s): [@edballou](https://github.com/edballou)
- Start Date: 2022-06-20
- Category: Economic
- Original HIP PR: https://github.com/helium/HIP/pull/XXX
- Tracking Issue: https://github.com/helium/HIP/issues/XXX

# Summary
[summary]: #summary

First and foremost, this HIP acknowledges the community's vote in favor of [HIP-39 Redenomination](0039-redenomination.md) and requires implementation of HIPs 51-53 in order for redenomination to be implemented fully. Complexities and complications in light of the time passed since the vote was done have changed the ability (and economic sense) to implement HIP 39 before August.

This also acknowledges Nova Labs & DeWi's formal responsibility in failing to execute HIP 39 implementation in a timely basis and encourages accountability for having roadmap commitments before the vote, with a deep need for explicit policy to be determined for renegotiating priorities when votes are complete and still require outstanding development work.

# Motivation
[motivation]: #motivation

The purpose is to codify the honoring (and its implementation) of the vote, and detail how HIP 39 will be implemented in HIPS 51-53. To make it clear, redenomination will not be implemented on $HNT, but rather how $IOT is implemented.

- Describe the known and unknown of economic conditions at the time of the vote and now
    - If token price falls below a certain threshold, it is removed automatically from some exchanges. Recent market movements would have seen this happen and currently for the only available means of interacting with Helium via $HNT.

- Describe what happened from a development perspective which demanded focus away from redenomination implementation
    - Finishing PoCv11, light hotspot implementation

- Describe why now is a better time to seek alternative methods for implementation of HIP 39 and how it will be done
    - With HIP 51 passed, this sets a more than likely precedent that HIPs 52-53 will pass.
    - The code is now written and has been for some time, it's just coordinating it to happen at the correct time.


# Stakeholders
[stakeholders]: #stakeholders

- Nova Labs: *TODO: link to vote guidance*
- Helium Foundation: *TODO: link to vote guidance*
- Helium Community discussion: *TODO: link to vote guidance*
- Exchanges: *TODO: link to vote guidance*

# Detailed Explaination
[detailed-explanation]: #detailed-explanation

- [A] Known and unknown economic conditions

  1) When token prices fall below thresholds, exchanges can automatically or by choice, delist tokens. As our only viable means of investing in Helium and the current loss of 85% of top price since HIP 39 was approved, this would have meant huge ramifications for $HNT.

  2) Binding all Helium activities to one token would increase volatility and speculation as various DAOs and applications, such as 5G, come online.

- [B] Development roadmap headwinds

  1) PoCv11 set up necessary improvements to the network to address valid coverage, institutional & isolated gaming, and pave way for more light hotspot support.

  2) Light hotspot support came at a crucial time when the network was struggling to stay up as the nodes and blockchain size became more unwieldy. Even still, some validators are struggling with proof of coverage analysis. It is expected that light hotspot support will continue, perhaps even toward upcoming offloading of proof of coverage validation.

  3) Referring back to [A.2], binding all development activities back to one token could cause unforeseen loss of integrity, gaming, etc. In order to nimbly implement omni-protocol support, developers need HIPs 51-53 to protect protocol specific changes and eliminate abstraction overhead.

- [C] Honoring HIP 39 through HIPs 51-53

  1) Joey Hiller confirms implementation has been ready for quite some time and is currently targeting August of 2022 for implementation. *TODO: for reasons*

  2) Here are specific places HIP 39 has been codified to be implemented in HIP 51-53:

     *TODO: lots of research & highlighting*

# Drawbacks
[drawbacks]: #drawbacks

- It would NOT affect $HNT, which was the intent of HIP 39

# Rationale and Alternatives
[alternatives]: #rationale-and-alternatives

This is your chance to discuss your proposal in the context of the whole design
space. This is probably the most important section!

- HIP 39 could still be moved forward and implemented.

# Unresolved Questions
[unresolved]: #unresolved-questions

- How will the above be implemented techinically speaking.
