# Bible Explorer

An interactive Bible library in a single web page. The Library tab maps all 66 books, and each built passage gets its own hands-on tab:

| Tab | Passage | What you can do |
|---|---|---|
| **Words of Jesus** | Matthew, Mark, Luke, John | 130 sayings of Jesus sorted into 13 themes, 14 life situations ("I'm anxious", "Someone hurt me", "I have doubts"…) and 7 study paths (Sermon on the Mount, the "I am" sayings, words from the cross…). Each has its meaning in plain words, one way to live it today, parallel accounts, a word for today, and save / "I did this today" tracking |
| In the Beginning | Genesis 1–3 | Speak light into the dark, watch creation build day by day, name the animals, search the garden |
| Through the Sea | Exodus 12–14 | Mark the doorframe, pack for the road, follow the route, cross the sea |
| The King Has Come | Matthew 1–28 | The whole book: the King and his kingdom, a chapter map, people who met Jesus, and his words by theme |
| The Servant Who Came to Give | Mark 1–16 | The whole book: the servant Son of God, a chapter map, and his words by theme |
| No King in Israel | Judges 1–21 | The whole book: the repeating cycle, twelve judges charted, Deborah, Gideon's 300, Samson, and the dark ending |
| For Such a Time | Esther 1–10 | The whole book: the empire at a glance, the cast lot, the relay through Hathach, a sleepless night, six reversals and the days of Purim |
| A Savior for Everyone | Luke 1–24 | The whole book: the Savior who seeks the lost, a chapter map, and his words by theme |
| The Third Day | Luke 22–24 | The upper room, Peter by the fire, the three courts, roll the stone, walk to Emmaus |
| That You May Believe | John 1–21 | The whole book: seven signs, seven "I am" sayings, the upper room, a chapter map, and his words by theme |
| The Word Became Flesh | John 1–3 | Question John the Baptist, fill the six jars at Cana, the night wind with Nicodemus |
| Wind and Fire | Acts 1–2 | The ascension, casting lots, fifteen nations hearing in their own language, three thousand added |
| No Condemnation | Romans 3–8 | Paul's argument as seven steps, from "all under sin" to a love nothing can break |
| All Things New | Revelation 21–22 | The city coming down, its gates and jewels, the river and tree of life, back to Eden |

## Four ways to view the Bible

A switch at the top of the page changes how you see the whole Bible:

- **By book**: the Library of all 66 books and every study tab (what is listed below).
- **God's plan**: a timeline of five eras, from Adam to eternity: Deity-consciousness (Adam to Noah), Sacrifice (Noah to Moses), Law (Moses to Jesus), Grace (Jesus to the second coming, marked "We are here") and the Millennium (to the great judgment), then the new heaven and earth. Tap an era for how people came to God, what God was doing, key events with verses, the people, where to read it, and which study tabs belong there.
- **God's character**: eighteen attributes in two rings, what God is like (love, grace, mercy, compassion, truth, righteousness, justice, uprightness, faithfulness, peace, hope) and who he is to us (Father, Shepherd, Rock, Vine, King, Master and Lord, Source of all things). Each has key verses, what it means for you today, a prayer, the stories that show it, and what Jesus said.

- **Church life**: how to live as the church, in nine areas: Christ and the church (head and body, bridegroom and bride, cornerstone and living stones, vine and branches, shepherd and flock), the authority of the church, shepherds and the flock, one body with many members, gathering and worship, baptism and the Lord's Supper, giving and serving, restoring someone who falls, and being sent into the world. Each has Scripture and a "how to live it" checklist you can tick, plus the sixteen "one another" commands.

## The heart of each story

Every passage tab opens with a lesson layer:

- **One core word and lesson** for the whole passage (Esther: *Surrender*, Exodus: *Deliverance*, Romans: *Grace* and so on).
- **The shape of the story**, a chart of hope rising and falling across the seven scenes, with the turning point marked. Tap a scene to read its takeaway and jump to it.
- **Character cores**: each key person's defining trait and moment (with the verse), marked *Follow this*, *Beware* or *Learn from both sides*, plus what it means for us.
- **A takeaway in every scene**, and **Take it home** reflection questions before the quiz.

Lessons are interpretation and are labelled that way; the moments they rest on are cited.

## How it works

- One file, `index.html`, with no build step and no outside libraries. Open it in any browser, or serve it with GitHub Pages.
- Every claim has a gold reference. Tapping it shows the verse and the page in the NIV PDF it was checked against.
- Text is retold in plain words, with only short direct quotes (a signature line per key character). Labels mark what is an illustration, an observation, a calculation or an interpretation.
- Remembers where you stopped, has light and dark modes and adjustable text size, and works on phones.

## Publishing with GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`. The site appears at `https://nansc01.github.io/bible-explorer/`.

## Adding a passage

Pick chapters in the Library tab, copy the request it writes, and ask Claude to add it as a new tab.

Scripture paraphrases are based on the New International Version (NIV).
