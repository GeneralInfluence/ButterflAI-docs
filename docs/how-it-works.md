# How ButterflAI works

## The idea

**The assistant does the logistical labor of friendship so you can do the emotional labor.** Finding a time, checking who's
free, keeping track of who's bringing what, noticing it's been a while — that's ButterflAI's job. What you say to a friend,
how you show up, whether you go — that stays yours.

Everything else follows from that line.

## Your own ButterflAI

Everyone has their own ButterflAI. It knows what you tell it — your plans, your friends as you name them, what you like,
when you're free if you connect a calendar — and it works only for you. You talk to it in plain language, by typing or by
voice, and you can show it things: a screenshot of a group chat, a flyer, an event page, a file with a list.

Before it replies, it reads your message into the things you're asking for (a plan, a change, a yes, a step to add) and does
the ones that are clear. Then it tells you what it did, so you can undo anything it got wrong.

## Plans are shared objects

A plan is not a chat thread. It's one object everyone in it works on, with the same fields for everyone:

| Field | What it holds |
|---|---|
| **What** | A name and a one-line summary of what's happening |
| **When** | A day and time — or a part of the day ("evening"), or options still being decided |
| **Where** | A place, or "not set yet" |
| **Who** | Who's in, who's thinking about it, who can't make it, who's hosting |
| **Steps** | The things to do to make it happen, and anything inside them (a shopping list and what's on it) |

Every detail is either **proposed** (someone floated it) or **agreed** (the host settled it), and every detail keeps **the
words that set it** — so anyone in the plan can tap "when" and see who said "Friday evening", and when. ButterflAI only fills
in details someone actually said; if nobody gave a time, the plan says "evening" or "time TBD", not a made-up 7 pm.

Hosts and co-hosts decide; guests suggest. A change by anyone reaches everyone in the plan, and the plan shows who has seen
it. A plan can be made of moments — Friendsgiving holds "shop together Wednesday", "cook the sprouts at Sam's" and the
dinner itself. Each moment has its own when, where and who (just the people doing it); everyone in the plan sees the whole
schedule, and it's all one conversation.

## Assistants coordinate so people don't have to

When a plan involves friends who also use ButterflAI, the assistants work it out between them: is Friday free, does anyone
have a constraint, who's bringing dessert. **People only hear from their own ButterflAI** — never a message from someone
else's assistant — and only about things that need them. Your ButterflAI never says yes for you; it tells your friend's
ButterflAI what it actually knows.

Some things go between assistants as a quiet heads-up instead of a question: "maybe we'll do it tonight" puts the plan on
your friend's list as possible without asking them anything.

## People who aren't on ButterflAI

ButterflAI only texts people who have asked it to. For a friend who isn't on ButterflAI, it writes the invite in your voice
and you send it from your own phone — they answer you, and you tell your ButterflAI.

## Explore

Explore is a feed of ideas made for you: real things happening near you (only from pages that open securely), ways to see a
friend you haven't seen in a while, something new to try. You can search it, react to ideas, save the ones you're into, and
turn any of them into a plan. What you like shapes what it finds next.

## Where it runs

ButterflAI is a web app you add to your phone's home screen. It's built on Anthropic's Claude models. It reaches you in the
app first, with notifications; it texts you only if you've opted in and haven't seen something in the app.
