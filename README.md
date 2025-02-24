# {TOPICAL_NAME} Prompts
### - {TOPICAL_SLOGAN}

{TOPICAL_IMAGE}
{TOPICAL_IMAGE_COPYRIGHT}

---
## {TOPICAL_GOAL}

> {TOPICAL_STATUS_NOTE}

# Showcase 
> {TOPICAL_SHOWCASE}

## What is this?
 - a **[rocketa](https://github.com/nostogome/rocketa)** `topical repository`

## What's the topic?
 - *"{TOPICAL_GOAL_SHORT}"*
    - See [repository.md](repository.md) for more information
- The main goal of this project is the [`prompts`](https://{TOPICAL_HOST}/{TOPICAL_USERNAME}/{TOPICAL_REPO_NAME}/prompts) 'artifacts' directory

## Quick example, chats
See [github.com/nostogome/rocketa/chats/org.nobodyknows/tdd/1.0.0/AAA/chat.md](https://github.com/nostogome/rocketa/chats/org.nobodyknew/tdd/1.0.0/AAA/chat.md) 

# Repo Use and Rules
## Usage flow

General Usage by flow order, but not necessarily. All have `full coordinate ability` (i.e. dir structure)
- Chats
  - conversations starters, usually never leave versions 1.0.0
- Conversations
  - more formal, forkable conversation flows supported by `hash-versioning` (commonly used more like 'git commit hash' than a -SNAPSHOT, but no rules enforced).  Parent dir has a current pointer file, named `current`
- Prompts
  - output, generated or otherwise 

## *chats* (informal, with or w/o responses, messier than conversations)
`./chats` informal chats with optionally *included* responses.  Intended to be mind-forked, and includes some examples.  Please recontribute to this (organized), and to conversations (final products without the LLM responses).

## *conversations* (formal, hint of more longevity/forking value - with or without responses)
`./conversations` releasable conversations that may have optional *included* (partial) responses - which lead to creation of artifacts in `./prompts`  - they are generally intended for creative sharing and to foster iteration. A metadata file is included for citing sources in `metadata.md` which lives at the `artifact`, `version`, and/or `hash` level.  This is for automated doc tree building.  There is also a `summary.md` file that contains priority information (e.g. printed first in doc tree build).  If releasing, include the coordinate of the `chats`, if applicable, in the frontmatter.

## *prompts* (actual responses - with or without actual responses)
`./prompts` contain releasable prompts for specifically versioned creations. group/artifact/version/hash/ (e.g. *com.bytesalot/superbeing/1.0.2/8ffjeu3basdoh/*).  If releasing, include the coordinate of the `conversations` and `chats`, if applicable, in the frontmatter. See [https://github.com/nostogome/rocketa/README.md](https://github.com/nostogome/rocketa/README.md#frontmatter-keys)

## About automated citation and documentation rendering

## Downstream
Links to projects that are > ~80% direct result of using existing (i.e. *committed*) prompts [nostogome/rocketa/prompts](https://github.com/nostogome/rocketa/prompts).  Topical repositories may or may not choose have this policy.

| Name | URL | Description | Use | Replaces target | Results |
|------|-----|-------------|-----|-----------------|---------|
| example | github/mygen | prompt generates entire project | Maven archetypes | Works, sometimes.  Looking forward to new models or langchain integrations |


## Content policy
- Refer to content policy in [repository.md](repository.md)

## Accepting Pulls, Maintenence, Deletion
- The **[rocketa spirit](https://github.com/nostogome/rocketa/README.md#rocketa-spirit)** identifies some ideas to enable fasttracking/PR automation
  - strip `<` (raw AI output) for fastest (automated, even) PR inclusion
  - if `<` (raw AI output) are included, explain why **upfront** to make `triage` easy
    - obvious caveat when AI response ***is the topic*** ;)
- Entries may disappear at any time, including but not limited to 
  - Maintenence, including Pruning
  - Removing previously accepted content due to changes in the Content Policy, as defined in `repository.md` or other `nostogome/rocketa` statements or will

## Pruning
 - won't prune `current` or those with a newer commit timestamp than the `current` file pointer

# Extended Frontmatter Information
 
# License

Most content released under MIT license with exception of the /site directory, and other branding-related content and images specific to github.com/nostogome/rocketa

See [NOTICE](NOTICE), [LICENSE](LICENSE) for details
