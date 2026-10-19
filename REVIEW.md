# Strict review of the TOK exhibition skill

Reviewed: 19 October 2026.

Artifact: [tok-exhibition-writer/SKILL.md](SKILL.md).

## Method and limits

This was a manual adversarial walkthrough of the instructions, checked against the exhibition guidance on pages 5-8 of the supplied `Tok-exhi.pdf`. It was not an independent examiner assessment, an independently executed model benchmark or a live ZeroGPT trial. The fragments and detector responses below are synthetic test inputs. No student exhibition was uploaded to an external service.

The skill's existing source register remains its research basis. This review did not reread all 17 exhibitions or enlarge that research set. The review focuses on the gap between giving sound advice and specifying decisions that prevent plausible failures.

## Examiner findings and repairs

The original skill already prioritised specific contexts, justified prompt links, evidence, a holistic assessment and a 950-word ceiling. Its main weakness was operational: an assistant could comply superficially by adding an object's name and date, then write a generic discussion. It also prohibited harmful detector edits without defining a reliable comparison and rollback process.

The revised skill now distinguishes identification, explanation of the link and justification of the particular contribution. It requires a working evidence map and four diagnostic questions: substitution, inferential bridge, scope and contribution. These are drafting aids, not additional IB criteria or independently scored components. They do not require an irreplaceable object, a personal connection, compulsory counterclaims or explicit comparisons.

For detector revisions, it now preserves accepted versions, reviews a candidate before adopting it, and checks that the final commentary exactly matches the version associated with the reported result. The desired detector threshold remains below 15%, subject to accuracy, quality and a finite revision budget.

## Object-analysis walkthroughs

The fragments below are diagnostic material, not suggested exhibition objects.

| Case and supplied fragment or condition | Decision reached using the revised skill | Failure addressed |
| --- | --- | --- |
| 1. Decorative specificity: "I encountered this object in 2019. It shows that knowledge changes over time." No further evidence of a change is supplied. | The date situates an encounter but does not establish a change in knowledge. Request the relevant supported detail or narrow the interpretation. Do not invent a before-and-after history. | A specific opening can conceal generic analysis. |
| 2. Missing warrant: "It came from an expert, so the claim must be true." | Authority alone does not support the certainty claimed. Examine what the supplied material actually establishes about grounds for trust; separate acceptance from truth. | A conclusion can overreach an otherwise factual premise. |
| 3. Personal attachment as justification: "I included it because it is important to me." | Personal importance needs an explained connection to the knowledge issue and prompt. Ask about the relevant confirmed experience without suggesting an anecdote. | Attachment is not automatically analytical justification. |
| 4. Citation as substitute for reasoning: a sourced detail is followed by an unsupported universal conclusion. | Check the source's scope and supply the missing inference only if warranted. A reference marker cannot repair a logical gap. | Accurate citation can coexist with weak analysis. |
| 5. Repetition: three supplied objects each conclude only that people have different perspectives. | Identify what each context supports about the mechanism, conditions or implications. If no distinct development is supported, disclose the limitation without inventing differences or suggesting replacements. | Variety of objects is not necessarily variety of contribution. |
| 6. Similarity: three supplied objects are similar, but their contexts support different mechanisms. | Retain the supported contributions. Do not demand three categories or penalise similarity itself. | The substitution diagnostic must not become a novelty requirement. |
| 7. Prompt drift: accurate history and an interesting ethical debate do not explain the selected knowledge question. | Trim background and recover the supported connection to the operative terms of the prompt. Do not reward sophistication unrelated to the task. | Topic expertise can displace TOK analysis. |
| 8. Symbolic shortcut: an appearance is said to "represent uncertainty", without a connection to knowledge in the object's actual context. | Treat this as an unsupported symbolic link. Ask for relevant context or acknowledge the limitation. | Metaphor can replace a real-world explanation. |
| 9. A student endorses an interpretation containing an unsupported public historical claim. | Approval confirms the intended interpretation, not the historical premise. Verify, remove or resolve that premise. | Confirmation can be mistaken for evidence. |
| 10. Two developed sections and a thin third section, with 970 commentary words. | Review the whole exhibition and rebalance space. Trim repetition and background before deleting warrants, qualifications or essential third-object analysis. Recount to no more than 950. Do not invent an automatic numerical ceiling based on one section. | Polishing and compression can disproportionately weaken one object. |
| 11. Two images are supplied and the student requests the complete draft immediately. | Continue limited feedback and request the third selected object's image. Do not produce a complete image-dependent draft or propose a third object. | Full drafting must respect the creator's image requirement. |

The image gate in case 11 is a creator-specified workflow rule. It should not be represented as an automatic IB marking penalty for an otherwise identifiable object without an image.

## Detector-process walkthroughs

| Case and synthetic input | Decision reached using the revised skill |
| --- | --- |
| 12. Valid fresh AI/GPT results of 14.9% and 15.0%. | 14.9% meets the requested threshold; 15.0% does not. Neither predicts the exhibition's mark. |
| 13. "Human: 88%", with no unambiguous AI/GPT metric. | Do not invert the number to invent a 12% result. Treat the required result as unavailable or ambiguous. |
| 14. Input was truncated, or the display still shows the prior submission's result. | Do not associate that result with the intended full commentary. Verify complete input and a fresh completed result. |
| 15. A result of 28% has no accessible highlights. | Do not guess which passages were flagged. Seek the actual highlights or stop the targeted loop and report the limitation. |
| 16. Highlighted prose says "may influence acceptance"; a proposed revision says "determines truth". | Reject the candidate before submission. It changes both the strength and object of the claim. Keep the accepted master. |
| 17. A proposed revision removes the only supported contextual detail or the sentence explaining its significance. | Reject or repair the regression, even if a hypothetical detector score would be lower. Preserve the detail's analytical role. |
| 18. A supported direct quotation is highlighted. | Do not silently rewrite it inside quotation marks. Preserve it, or make a faithful attributed paraphrase only when that is a sound writing choice. Preserve citation alignment. |
| 19. A proposed revision moves a citation next to a stronger claim the source does not support. | Reject or repair the claim and reference alignment before checking the candidate. |
| 20. An unchanged draft is resubmitted repeatedly to obtain a favourable score. | Do not run this sequence. The loop permits defensible revisions, not repeated score hunting. |
| 21. Five candidate revision rounds have occurred; one candidate was rejected and another failed submission. | Both still consume rounds. Do not reset the budget through rollback, a manual check or a new version label. Deliver the strongest supported version with an honest status. |
| 22. A checked 12% draft is subsequently reworded or has punctuation changed. | Its result is stale for the revised input. Recheck within budget or label the delivered version unchecked. |
| 23. The strongest retained version scored 19%; a weaker discarded version scored 11%. | Return the stronger version and report 19%, with the target unmet. Never attach the discarded version's result to it. |
| 24. The student supplies a result from their own check. | Record it as student-reported and associate it only with the exact version they checked. Do not claim direct verification. |

### Citation-removal fixture

Synthetic master fragment:

> The change occurred in 2019 (not 2020). Its reported value was (1 + 2), rather than 4. The account describes the sequence (Lee, 2021, p. 4), but the sequence alone does not establish its cause. The [stated limitation](https://example.com/source) remains relevant.

Expected detector text, manually worked through:

> The change occurred in 2019 (not 2020). Its reported value was (1 + 2), rather than 4. The account describes the sequence, but the sequence alone does not establish its cause. The stated limitation remains relevant.

The bibliographic parenthesis and link apparatus are removed. Dates, mathematical content, qualification, substantive linked words and paragraph order remain. The URL is a test placeholder, not an exhibition source. Real sources must be checked under the skill's citation rules. A genuine numbered reference such as `(1)` is removed only when it is identified as a reference, not by a blanket rule that deletes parenthetical numbers.

## Validation and remaining uncertainty

The revised skill passed the skill-creator structural validator. The file was also checked for prohibited em dashes, and none were present. These checks establish file validity and the specific character constraint; they do not validate future exhibition quality.

The walkthroughs found explicit decision paths for the failure cases above. They do not demonstrate that every host model will follow the instructions or that ZeroGPT will return a particular score. No complete exhibition was generated or independently marked in this review, because this task supplied no new student-selected set of three objects and images for such a trial. A future end-to-end trial would need those inputs and their confirmed interpretations. A 9-10/10 result remains dependent on the material, execution and examiner judgment.
