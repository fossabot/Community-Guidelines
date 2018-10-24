# Governance

* [Overview](#overview)
* [Code of conduct](#code-of-conduct)
* [Roles and responsibilities](#roles-and-responsibilities)
  * [Users](#users)
  * [Contributors](#contributors)
  * [Committers](#committers)
    * [Current committers](#current-committers)
  * [Project management committee](#project-management-committee)
    * [Current project management committee](#current-project-management-committee)
* [Support](#support)
* [Contribution process](#contribution-process)
* [Decision making process](#decision-making-process)
  * [Lazy consensus](#lazy-consensus)
  * [Voting](#voting)
  * [Types of approval](#types-of-approval)
  * [When is a vote required?](#when-is-a-vote-required)
* [Conclusion](#conclusion)
* [Attribution](#attribution)

## <a name="overview"></a>Overview

This is a meritocratic, consensus-based community project. Anyone with an interest in the project can join the community, contribute to the project design and participate in the decision making process. This document describes how that participation takes place and how to set about earning merit within the project community.

An important distinction is that all participants in OpenAIM are participating as individuals. A stregth of OpenAIM is open participation and that affiliation to an employer or other organizations do not cloud the personal contributions. Unless specifically stated otherwise, anything posted on GitHub or the OpenAIM Discussion Portal is done as the individual speaking on their own behalf. OpenAIM participants carry many different roles and responsibilities, including as Users, Contributors, Committers, and as on the Project Management Committee. What matters here is the opinion and experience of the individual and their participation with the community. 

## <a name="code-of-conduct"></a>Code of conduct

This community project aims to be an open and welcoming environment experience for everyone. All community members must follow the [code of conduct](CODE-OF-CONDUCT.md).

## <a name="roles-and-responsibilities"></a>Roles and responsibilities

### <a name="users"></a>Users

Users are community members who have a need for the project. They are the most important members of the community and without them the project would have no purpose. Anyone can be a user; there are no special requirements.

The project asks its users to participate in the project and community as much as possible. User contributions enable the project team to ensure that they are satisfying the needs of those users. Common user contributions include (but are not limited to):

*   evangelising about the project (e.g. a link on a website and word-of-mouth awareness raising)
*   informing developers of strengths and weaknesses from a new user perspective
*   providing moral support (a ‘thank you’ goes a long way)
*   providing financial support (the software is open source, but its developers need to eat)

Users who continue to engage with the project and its community will often become more and more involved. Such users may find themselves becoming contributors, as described in the next section.

### <a name="contributors"></a>Contributors

Contributors are community members who contribute in concrete ways to the project. Anyone can become a contributor and contributions can take many forms. There is no expectation of commitment to the project, no specific skill requirements and no selection process.

In addition to their actions as users, contributors may also find themselves doing one or more of the following:

*   supporting new users (existing users are often the best people to support new users)
*   reporting bugs
*   identifying requirements
*   providing graphics and web design
*   programming
*   assisting with project infrastructure
*   writing documentation
*   fixing bugs
*   adding features

Contributors engage with the project through the issue trackers and dicussion portal, or by writing or editing documentation. They submit changes to the project itself via patches, which will be considered for inclusion in the project by existing committers (see next section). The [OpenAIM Discussion Portal](https://discuss.openaim.io) is the most appropriate place to ask for help when making that first contribution.

As contributors gain experience and familiarity with the project, their profile within, and commitment to, the community will increase. At some stage, they may find themselves being nominated for committership.

### <a name="committers"></a>Committers

Committers are community members who have shown that they are committed to the continued development of the project through ongoing engagement with the community. Committership allows contributors to more easily carry on with their project related activities by giving them direct access to the project’s resources. That is, they can make changes directly to project outputs, without having to submit changes via patches.

This does not mean that a committer is free to do what they want. In fact, committers have no more authority over the project than contributors. While committership indicates a valued member of the community who has demonstrated a healthy respect for the project’s aims and objectives, their work continues to be reviewed by the community before acceptance in an official release. The key difference between a committer and a contributor is when this approval is sought from the community. A committer seeks approval after the contribution is made, rather than before.

Seeking approval after making a contribution is known as a commit-then-review process. It is more efficient to allow trusted people to make direct contributions, as the majority of those contributions will be accepted by the project. The project employs various communication mechanisms to ensure that all contributions are reviewed by the community as a whole. By the time a contributor is invited to become a committer, they will have become familiar with the project’s various tools as a user and then as a contributor.

Anyone can become a committer, the requirements include:
* having demonstrated a willingness and ability to participate in the project as a team player
* experience using GitHub utilizing the GitHub Flow process
* a deep understanding of the project, its objectives, and its strategy
* having provided valuable contributions to the project through GitHub over a period of time

New committers can be nominated by any existing committer. Once they have been nominated, there will be a vote by the project management committee (PMC; see below). Committer voting is one of the few activities that takes place on the project’s private management list. This is to allow PMC members to freely express their opinions about a nominee without causing embarrassment. Once the vote has been held, the aggregated voting results are published on the public mailing lists. The nominee is entitled to request an explanation of any ‘no’ votes against them, regardless of the outcome of the vote. This explanation will be provided by the PMC Chair (see below) and will be anonymous and constructive in nature. 

Nominees may decline their appointment as a committer. However, this is unusual, as the project does not expect any specific time or resource commitment from its community members. The intention behind the role of committer is to allow people to contribute to the project more easily, not to tie them in to the project in any formal way.

It is important to recognise that commitership is a privilege, not a right. That privilege must be earned and once earned it can be removed by the PMC (see next section) in extreme circumstances. However, under normal circumstances committership exists for as long as the committer wishes to continue engaging with the project.

#### <a name="current-committers"></a>Current committers

* [Jay Merlan, @jmerlan](https://github.com/jmerlan)
* [Van Woods, @vdubya](https://github.com/vdubya)
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])

A committer who shows an above-average level of contribution to the project, particularly with respect to its strategic direction and long-term health, may be nominated to become a member of the PMC. This role is described below.

### <a name="project-management-committee"></a>Project management committee

The project management committee consists of those individuals identified as ‘project owners’ on the development site. The PMC has additional responsibilities over and above those of a committer. These responsibilities ensure the smooth running of the project. PMC members are expected to review code contributions, participate in strategic planning, approve changes to the governance model and manage the copyrights within the project outputs.

Members of the PMC do not have significant authority over other members of the community, although it is the PMC that votes on new committers. It also makes decisions when community consensus cannot be reached. In addition, the PMC has access to the project’s private mailing list and its archives. This list is used for sensitive issues, such as votes for new committers and legal matters that cannot be discussed in public. It is never used for project management or planning.

Membership of the PMC is by invitation from the existing PMC members. A nomination will result in discussion and then a vote by the existing PMC members. PMC membership votes are subject to consensus approval of the current PMC members.

The PMC Chair is a single individual, voted for by the PMC members. Once someone has been appointed Chair, they remain in that role until they choose to retire, or the PMC casts a two-thirds majority vote to remove them.

The PMC Chair has no additional authority over other members of the PMC: the role is one of coordinator and facilitator. The Chair is also expected to ensure that all governance processes are adhered to, and has the casting vote when the project fails to reach consensus.

#### <a name="current-project-management-committee"></a>Current project management committee

* PMC Chair: * [Jay Merlan, @jmerlan](https://github.com/jmerlan)
* [[Van Woods, @vdubya](https://github.com/vdubya)
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])
* [FirstName Lastname, @GitHubUserName](https://github.com/[username])

## <a name="support"></a>Support

All participants in the community are encouraged to provide support for new users within the project management infrastructure. This support is provided as a way of growing the community. Those seeking support should recognise that all support activity within the project is voluntary and is therefore provided as and when time allows. A user requiring guaranteed response times or results should therefore seek to purchase a support contract from a community member. However, for those willing to engage with the project on its own terms, and willing to help support other users, the community support channels are ideal.

## <a name="contribution-process"></a>Contribution process

Anyone can contribute to the project, regardless of their skills, as there are many ways to contribute. For instance, a contributor might be active on the mailing lists and issue trackers, or might supply patches.

Contributors can also help by providing feedback helping new users recommending the project to others, testing and reporting or fixing bugs, requesting new features, writing and updating software, creating artwork, writing or updating documentation, and translating.

The [OpenAIM Discussion Portal](https://discuss.openaim.io) is the most appropriate place for a contributor to ask for help when making their first contribution.

## <a name="decision-making-process"></a>Decision making process

Decisions about the future of the project are made through discussion with all members of the community, from the newest user to the most experienced PMC member. All non-sensitive project management discussion takes place on the [OpenAIM Discussion Portal](https://discuss.openaim.io). Occasionally, sensitive discussion occurs on a private list.

In order to ensure that the project is not bogged down by endless discussion and continual voting, the project operates a policy of lazy consensus. This allows the majority of decisions to be made without resorting to a formal vote.

### <a name="lazy-consensus"></a>Lazy consensus

Decision making typically involves the following steps:

*   Proposal
*   Discussion
*   Vote (if consensus is not reached through discussion)
*   Decision

Any community member can make a proposal for consideration by the community. In order to initiate a discussion about a new idea, they should send an email to the project contributors’ list or submit a patch implementing the idea to the issue trackers (or version-control system if they have commit access). This will prompt a review and, if necessary, a discussion of the idea. The goal of this review and discussion is to gain approval for the contribution. Since most people in the project community have a shared vision, there is often little need for discussion in order to reach consensus.

In general, as long as nobody explicitly opposes a proposal or patch, it is recognised as having the support of the community. This is called lazy consensus - that is, those who have not stated their opinion explicitly have implicitly agreed to the implementation of the proposal.

Lazy consensus is a very important concept within the project. It is this process that allows a large group of people to efficiently reach consensus, as someone with no objections to a proposal need not spend time stating their position, and others need not spend time reading such mails.

For lazy consensus to be effective, it is necessary to allow at least 72 hours before assuming that there are no objections to the proposal. This requirement ensures that everyone is given enough time to read, digest and respond to the proposal. This time period is chosen so as to be as inclusive as possible of all participants, regardless of their location and time commitments.

### <a name="voting"></a>Voting

Not all decisions can be made using lazy consensus. Issues such as those affecting the strategic direction or legal standing of the project must gain explicit approval in the form of a vote. Every member of the community is encouraged to express their opinions in all discussion and all votes. However, only project committers and/or PMC members (as defined above) have binding votes for the purposes of decision making.

If a formal vote on a proposal is called (signaled by posting to the [OpenAIM Discussion Portal](https://discuss.openaim.io#narrow/stream/14-Vote), all participants on the project contributor list may express an opinion and vote. They do this by replying to the original portal posting, with the following vote and information:

*   +1 ‘yes’, ‘agree’: also willing to help bring about the proposed action
*   +0 ‘yes’, ‘agree’: not willing or able to help bring about the proposed action
*   -0 ‘no’, ‘disagree’: but will not oppose the action’s going forward
*   -1 ‘no’, ‘disagree’: opposes the action’s going forward and must propose an alternative action to address the issue (or a justification for not addressing the issue)

To abstain from the vote, participants simply do not respond. However, it can be more helpful to cast a ‘+0’ or ‘-0’ than to abstain, since this allows the team to gauge the general feeling of the community if the proposal should be controversial.

Every member of the community, from interested user to the most active developer, has a vote. The project encourages all members to express their opinions in all discussion and all votes.

However, only some members have binding votes for the purposes of decision making; for example in the Apache Software Foundation these are the committers and/or the members of the _Project Management Committee_.

It is therefore their responsibility to ensure that the opinions of all community members are considered. While not all members may have a binding vote, a well-justified ‘-1’ from a non-committer must be considered by the community, and if appropriate, supported by a binding ‘-1’.

A ‘-1’ can also indicate a veto, depending on the type of vote and who is using it. Someone without a binding vote cannot veto a proposal, so in their case a -1 would simply indicate an objection.

When a vote receives a ‘-1’, it is the responsibility of the community as a whole to address the objection. Such discussion will continue until the objection is either rescinded, overruled (in the case of a non-binding veto) or the proposal itself is altered in order to achieve consensus (possibly by withdrawing it altogether). In the rare circumstance that consensus cannot be achieved, the PMC will decide the forward course of action.

In summary:

*   Those who don’t agree with the proposal and think they have a better idea should vote -1 and defend their counter-proposal.
*   Those who don’t agree but don’t have a better idea should vote -0.
*   Those who agree but will not actively assist in implementing the proposal should vote +0.
*   Those who agree and will actively assist in implementing the proposal should vote +1.

### <a name="types-of-approval"></a>Types of approval

Different actions require different types of approval, ranging from lazy consensus to a majority decision by the PMC. These are summarised in the table below. The section after the table describes which type of approval should be used in common situations.

<table>
    <thead>
        <tr>
            <th>Type</th>
            <th>Description</th>
            <th>Duration</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Lazy consensus</td>
            <td>An action with lazy consensus is implicitly allowed, unless
            a binding -1 vote is received. Depending on the type of action,
            a vote will then be called. Note that even though a binding -1
            is required to prevent the action, all community members are
            encouraged to cast a -1 vote with supporting argument.
            Committers are expected to evaluate the argument and, if
            necessary, support it with a binding -1.</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>Lazy majority</td>
            <td>A lazy majority vote requires more binding +1 votes than
            binding -1 votes.</td>
            <td>72 hours</td>
        </tr>
        <tr>
            <td>Consensus approval</td>
            <td>Consensus approval requires three binding +1 votes and no
            binding -1 votes.</td>
            <td>72 hours</td>
        </tr>
        <tr>
            <td>Unanimous consensus</td>
            <td>All of the binding votes that are cast are to be +1 and
            there can be no binding vetoes (-1).</td>
            <td>120 hours</td>
        </tr>
        <tr>
            <td>2/3 majority</td>
            <td>Some strategic actions require a 2/3 majority of PMC
            members; in addition, 2/3 of the binding votes cast must be
            +1. Such actions typically affect the foundation of the
            project (e.g. adopting a new codebase to replace an existing
            product).</td>
            <td>120 hours</td>
        </tr>
    </tbody>
</table>

### <a name="when-is-a-vote-required"></a>When is a vote required?

Every effort is made to allow the majority of decisions to be taken through lazy consensus. That is, simply stating one’s intentions is assumed to be enough to proceed, unless an objection is raised. However, some activities require a more formal approval process in order to ensure fully transparent decision making. The table below describes some of the actions that will require a vote. It also identifies which type of vote should be called.

<table>
    <thead>
        <tr>
            <th>Action</th>
            <th>Description</th>
            <th>Approval type</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Release plan</td>
            <td>Defines the timetable and actions for a release. A release
            plan cannot be vetoed (hence lazy majority).</td>
            <td>Lazy majority</td>
        </tr>
        <tr>
            <td>Product release</td>
            <td>When a release of one of the project’s products is ready, a
            vote is required to accept the release as an official release
            of the project. A release cannot be vetoed (hence lazy
            majority).</td>
            <td>Lazy majority</td>
        </tr>
        <tr>
            <td>New committer</td>
            <td>A new committer has been proposed.</td>
            <td>Consensus approval of the PMC</td>
        </tr>
        <tr>
            <td>New PMC member</td>
            <td>A new PMC member has been proposed.</td>
            <td>Consensus approval of the community</td>
        </tr>
        <tr>
            <td>Committer removal</td>
            <td>When removal of commit privileges is sought.</td>
            <td>Unanimous consensus of the PMC</td>
        </tr>
        <tr>
            <td>PMC member removal</td>
            <td>When removal of PMC membership is sought.</td>
            <td>Unanimous consensus of the community</td>
        </tr>
    </tbody>
</table>

## <a name="conclusion"></a>Conclusion

A clear and transparent governance document is a key part of any open development project. It defines the rules of engagement within the community and describes what level of influence a community member can expect to have over a project. In addition, it enables members to decide their level of involvement with that community. In the case of a meritocracy, it also provides a clear way to contribute and a highly visible reward system.

All that said, please remember that this project is your project. The point of this document is to grow the project by enabling, facilitating, and securing contributions in a manner that satisfies everyone. Pull requests and comments about the documents are always welcome, either here in the repository or in our community forums.


## <a name="attribution"></a>Attribution
The OpenAIM Governance is a derivative work of [Open Data Kit](https://github.com/opendatakit) and by extension the [Meritocratic Governance Model](http://oss-watch.ac.uk/resources/meritocraticgovernancemodel) by Ross Gardler and Gabriel Hanganu at University of Oxford. This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. OpenAIM content other than the OpenAIM Governance is subject to their own individual license terms.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>