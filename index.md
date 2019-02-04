# Minetest Mobs Mods

(just setting up!)

We are a group maintaining mods for [Minetest](https://minetest.net), an open source alternative to MineCraft-like games.

## Intended scope and benefits of this group

Our aim is to maintain mobs mods based on [tenplus1's `mobs_redo` mob engine](https://notabug.org/tenplus1/), keeping them in line with the upstream `mobs_redo` development. We aim to ensure mobs mods in the collection remain collectively compatible with the same version of `mobs_redo` as eachother, and that they can coexist in the same world as eachother.

## Submitting a mod

Because we intend to perform maintenance on mods in our repositories, we prefer not to be in commit-conflict with the original mod's repository. Ideally the original author will contribute their mod either because they wish to take a break from maintaining the mod for a period of time (they may or may not seek to have it returned to their own space at a later date), or they want to move the authoritative repository from their space to ours, whilst remaining its active maintainer. We may also take maintenance responsibility for mods that have been abandoned by their original authors.

For this reason, we will Pull-Request upstream on GitHub where possible; if the upstream developer(s) pursue development without integrating our changes over a significant period, we reserve the right to discontinue hosting a divergent version of the repository.

Mods should be submitted by their original creators ideally, though apparently-abandoned mods may be submitted too.

To submit a mod please:

* [open an Issue](https://github.com/minetest-mobs-mods/minetest-mobs-mods.github.io/issues)
  * Optionally: initiate a [Transfer Request](https://help.github.com/articles/transferring-a-repository/) on your repository to assign it to the `minetest-mobs-mods` organisation (this allows GitHub to redirect links to your old repository location to its new location in our group, as well as retaining likes and follows for subscribers)

### Requirements for submission acceptance

* Mod must add mobs based on `mobs_redo` - this is the core intended maintenance expertise of the group
   * Mods based on a mob engine that is otherwise intended to be compatible with `mobs_redo` may be accepted, on the understanding they will be adjusted to depend instead on `mobs_redo` features
* Mod must be fully and properly licensed:
    * No home-grown/self-written licenses can be accepted. Any non-GNU or non-OSI (for code), or non-CreativeCommons (for media assets) license should provide a link to the organisation that developed it. "Public domain" is not a license model that can be accepted.
    * Source code must be under a license that [is recognized by the OSI](https://opensource.org/osd)
        * Any WTFPL-licensed code will be re-licensed under MIT-license, the closest OSI-approved license in keeping with the intent of WTFPL.
    * Multimedia items including textures, sounds and models, must be distributed under their own explicit license, which grants recipients the right to redistribute in turn.
        * typically [`CC-BY`](https://creativecommons.org/licenses/by/4.0/), although [`CC0`](https://creativecommons.org/choose/zero/) is also acceptable.
    * Any submitted mod that is improperly licensed but abandoned will be reviewed on a case-by-case basis.
* Link to the mod's original online repository, or to where it can be downloaded, must be provided explicitly


### Abandoned mods

Mods submitted as "abandoned" need to either be stated so by the author ("I/we am/are no longer maintaining this") in a public forum, or in the submission Issue itself; or appear to have been abandoned for at least 6 calendar months, starting from the date of the last commit. Before implying a mod is abandoned, we will try to contact the original authors by any known means.

If the mod was improperly licensed (uncommon license, or license type without text or version), we will at our descretion attempt to identify a compatible license under which to re-license assets, compatible with any part-stated liceses. If none can be found, relevant assets may be dropped, or the mod rejected altogether. Mods not carrying any license statements may be systematically rejected.

### Author rights within this group

Authors will retain their original ownership rights and attribution. If said owners are known on GitHub at time of submission, they will automatcially be invited to join the group as contributors; but are not required to join for the mod to be accepted.
