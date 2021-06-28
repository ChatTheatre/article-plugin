%META:TOPICINFO{author=\"kallea\" date=\"1121194020\" format=\"1.0\"
version=\"1.1\"}% %META:TOPICPARENT{name=\"WebHome\"}% \<h1\>Article
System\</h1\>

[]{.twiki-macro .TOC}

## What is it?

The article system is a tool that SkotOS-enabled clients can use to
access external links from within the respective games. Each game can
have any amount of articles with descriptions, pointing anywhere on the
world wide web. For example, Arkham By Night has a set of articles from
the lovecraftcountry.com website linked from within the game. A user of
Alice of Zealous may access either of these with a simple mouse-click,
and references can be made from anywhere within the game system, where
SAM can be accessed or resolved.

------------------------------------------------------------------------

## How do the players use it?

The players use the \@article command to access the available articles
in the game. However, most of the article references are located within
help documents, login pages, tip nodes, and so on, giving the player the
option to click on a link and fire up an article. For example, the help
node for \"time\" in Arkham By Night links to an article on the
lovecraftcountry.com web site, which more in-depth brings up the topic
of \"how to relate to time\" in the game.

Articles can also be accessed directly. Typing `@article list` will show
a list of all the currently available articles. Clicking on either of
the articles will open a popup box leading to the specified URL.

    From the ABN server:
    > @article
    You can open articles related to the game using @article [article name].
    To see the available articles, type: @article list

    > @article list
    The following articles exist in the system right now:
    - <a target="_admpage" href="http://www.lovecraftcountry.com/images/uploads/ArkhamDetailedMap.jpg">Arkham Detailed Map</a>
    - <a target="_wtsspage" href="http://www.lovecraftcountry.com/home/help/article/wheres_the_scary_stuff/">Where's the Scary Stuff</a>
    >

------------------------------------------------------------------------

## How do the staffers use it?

The +article tool is a web interface used to maintain the current
articles data. It is a simple tool which allows you to add, modify and
delete articles available to the players.

When an article is modified, a submission date and a \"submitted by\"
property is set, allowing staff to know when an article was modified,
and by whom.

------------------------------------------------------------------------

## Notes on \@article versus \@help

In general, you want to avoid sending someone to a new window unless you
have to. In most cases, people should be referred to \@help articles
first. There are a number of articles on the lovecraftcountry.com that
should just modified to become \@help entries, and should not be
included in the +article list.

However, \@help articles should really not be very long, a screen or two
at most, which is often too short \-- it is in these cases where you can
add an \<acmd\> link to a longer \@article.

------------------------------------------------------------------------

\-- Main.KalleAlm - 12 Jul 2005
