Protocol Design on a Global Network
===================================

As designers and implementers of protocols that will be implemented on
the global Internet, we have responsibilities to think about the
impact of our decisions and the way that the protocols are structured.

This repo is an attempt to put together a coherent understanding of
those impacts and responsibilities.

We'll write mostly in markdown for now, and hopefully put together a
collection of relevant links as well.


Outline:

- Every context has a distribution of power. Technology when deployed in a
context can disrupt or can reinforce existing power distribution. These are
political outcomes.

- It's a fallacy to believe that you can design technology in a politically
neutral way by ignoring power relationships in the deployment
context. (Technological somnambulism)

- There is a power imbalance in the context of networked communications. There
is a small number of powerful network operators who control Internet
communications for a large number of not-so-powerful users. In various parts of
the world, the state has effective control over all operators available to
users. These users are subject today to the power of the network operators.

(There are also a small number of powerful users. But there are many more
disadvantaged users.)

- User interests are frequently not aligned with interests of the operators
available to those users. (EXAMPLES)

- We are Internet protocol designers. Internet protocols are used by people in
every country, and protocol design decisions are felt by people globally,
including users most at the mercy of the network operators.

- Network protocols can by their design shift the balance of power between the
parties involved.

- Building a protocol that has choice but is deployed in a context that has a
  strong power imbalance is effectively offering choice to only the powerful.

- As network protocol designers, we have an obligation to think about power
imbalances and to design towards remediating such imbalances.

- Run-time tussles allow for a range of different possible outcomes. Some of
these outcomes will be strengthen existing power differentials, some will weaken
them, and some will be neutral. If we want to remediate power imbalances, we
need to make design choices that constrain the run-time tussles.

Sidenote: We are talking about network protocol design in particular.  We
recognize that some users are more powerful than users, and in some cases some
users are more powerful than the biggest network operators.  Because network
operators have a gatekeeping role, that we need to take the needs of the
disadvantaged users as a priority. Other techniques may be required to address
the power of the more powerful users.

FIXME:
- Find better term than "user".
- rethink "powerless"

README:
- Dave Clark et al: Tussles in Cyberspace
- Langdon Winner: Technology as forms of life
- Langdon Winner: Do Artifacts Have Politics
