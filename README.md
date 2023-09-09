# Preparing4life
Repo for software related to podcasting

First phase of this project will be to create a feed.xml compliant with Podcasting 2.0 Namespace.
* https://github.com/Podcastindex-org/podcast-namespace/blob/main/example.xml
* This will use a local SQLite database to store podcast and episode information.
* After each episode enter information and then click publish.
* It should then generate the feed.xml for you. You will need to manually publish.

Second phase will include publishing.
* I will attempt to add ability to publish to IPFS
* I might also include other publishing destinations
* Upon clicking the publish button it will then copy your .mp3 episode and feed.xml to destination
* It will also try to update Podcast Index 2.0 with your feed.xml containing new episode information.
* Maybe try to include other lists like iTunes.
