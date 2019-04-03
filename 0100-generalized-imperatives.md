- Feature Name: `ko'oi`
- Start Date: yyyy-mm-dd
- RFC Pull Request: (leave this empty)
- Current Status: draft proposal

**This proposal is non-standard, pending adoption by the LFK and ratification
by the LLG.**

# Summary
[Summary]: #summary

This proposal adds the word `ko'oi`(in selma'o `UI`) as a generalization of
imperatives. `ko'oi` is a universal imperative marker, and when applied to a
sumti marks the target of the command; `ko` expands to `do ko'oi`.


# Background and Motivation
[Background and Motivation]: #background-and-motivation

The Lojban systems for dealing with commands are a relatively weak part of the
language. Currently, one can only give commands to the listener(s), by using
`ko` instead of `do`. Alternatively, one could use `.e'o`, which marks a
request. However, the CLL uses `.e'o` *in addition* to `ko`, suggesting that
`.e'o` on its own does not turn a bridi into a command. Furthermore, the range
of uses of `ko` is substantially broader than `e'o`, covering all cases in which
it is the desired effect of the sentence is that some party will comply with it.
This can encompass `.e'o`, `.au` (desire), `.ei` (obligation), or even in the
right circumstances other attitudes such as `.e'u` (suggestion). In this
proposal, `ko'oi` is added, which has the full range of meaning of `ko` but can
apply to pronouns other than `do`, or even to the sentence as a whole.

This change is beneficial for several reasons. It plugs a hole in the language,
as `ko` is currently exceptional in being available solely in second person.
There is no other instance where a specific propositional attitude is associated
with a specific pronoun. Requiring that the imperative/hortative attitude can
only occur if the person who is being talked to is the same as the one being
commanded is unduly restrictive and makes Lojban less regular. Other
propositional attitudes are expressed through selma'o `UI`, and this proposal
brings the language into conformance with that expectation, provided that `ko`
is taken as an abbreviation for `do ko'oi`.

It also increases cultural neutrality. Many languages provide some form of
imperative construction in the third and first person. Ancient Greek has third
person imperatives, and Irish and Turkish have imperatives in all three persons.
Furthermore, many languages that do not provide imperatives in the first and
third persons provide jussive constructions which carry a similar force. Such
languages include English, Latin, Arabic, and Russian. In Esperanto, the
imperative and jussive moods are unified into a volitive mood. In short, in the
current state of affairs Lojban makes a distinction that is far from universal
among other languages. While it may be true in English that there is a
distinction between the imperative and jussive moods, there is no reason to
continue this distinction in Lojban. Unifying on the Esperanto model allows
constructions from any of these languages to be translated into Lojban.


# Guide-level Explanation
[Guide-level Explanation]: #guide-level-explanation

To express an command directed at someone other than the listener, you can use
`ko'oi`. In fact, `ko` is just short for `do ko'oi`. Here are some examples:

`mi'o ko'oi klama`
Let's go!
*Note: This is short for "let us go". "Let X do Y" is a useful translation
for many uses of `ko'oi`.*

`le jenmi ko'oi cu gunta le bradi`
The army shall attack the enemy!

You can even put it on the sentence as a whole, not marking any specific target,
like this:

`.i ko'oi le jenmi cu gunta le bradi`
Let it come to pass that the army attacks the enemy!

This change is not expected to change the meaning of anything you can
currently say; it will merely allows some expressions that were not
previously allowed.


# Reference-level Explanation
[Reference-level Explanation]: #reference-level-explanation

`ko'oi` is added as a member of selma'o `UI6`. Definition:
```
discursive: imperative/hortative; attached to a sumti indicates that the
sumti is the target of the command; generally, indicates a general sense of
urging or commanding that the bridi take place.
```

A note should be appended to the definition of `ko` specifying that it expands
to `do ko'oi`.


# Drawbacks
[Drawbacks]: #drawbacks

This adds a new cmavo, which may prove not to be justified. Additionally,
this allocates a cmavo in the experimental range, which could be considered
a negative. That problem is considered more below.


# Alternatives
[Alternatives]: #alternatives

Assigning a new cmavo in the stable range, rather than using an experimental
form, was considered and rejected for three reasons:

  1. There isn't much non-experimental cmavo space left.
  2. `ko'oi` has a form resembling that of `ko`, which would likely be lost
     if a stable cmavo was found.
  3. People have been using `ko'oi` for a long time. Changing it up means that
     they will have to learn a new cmavo, and that anyone who reads old stuff
     that uses the old form will not know what's going on. Obviously, the usage
     is experimental, so we don't have to support it, but it's less confusing
     for everyone if we do.

The strategy currently proposed has the disadvantage that the morphological
distinction between experimental and stable usage is broken. In the opinion
of the author, maintaining this distinction isn't worthwhile in light of
the above concerns, which are likely to apply similarly to many other
experimental cmavo.


# Unresolved Questions
[Unresolved Questions]: #unresolved-questions

There are no unresolved questions.

# Backwards Compatibility
[Backwards Compatibility]: #backwards-compatibility

This proposal is backwards compatible with all stable usage. It is incompatible
with any usage of `ko'oi` with a definition other than that described here;
no such usage is known to exist. This proposal would make `ko'oi` stable,
obliging us to maintain its definition in future.

# Credits
[Credits]: #credits

La guskant originally proposed this cmavo. The [Alternatives] section was
derived in part from a post by phma in the LLG 2018 Members Meeting on
Mattermost.
