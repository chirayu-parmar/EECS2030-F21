## Lab 4 is The Video Channel Platform Problem (e.g., YouTube)
**Lab design by Professor Chen-Wei(Jackie) Wang**

This object-oriented program is solving aspects of a video channel platform (e.g., YouTube), where each video channel has a number of followers, each of which being either one subscribed to the channel and watching videos as new ones are released, or one monitoring the channel's statistis (e.g., average watch time).

#### **The relevant entities involved in this problem:**
- Each video ***channel*** is characterized by its name (e.g., **Cafe Music BGM channel**), its list of followers, and its list of released videos. New followers may be added, and existing followers may be removed. When a channel is first created, it is specified with both the **maximum number of followers allowed** and the **maximum number of released videos allowed**. Periodically, a channel may update itself by releasing a video (e.g.,MONDAY MORNING JAZZ: Sweet November Jazz Music).

###### (a)Example Statistics of a Video Channel
- shows some example statistics of a video channel (e.g., views, watch time).
![4 1](https://user-images.githubusercontent.com/90284881/148714798-07e9fe5c-f1f4-4d36-b805-19bc6636ed1d.png)
###### (b) Multiple Channels Followed by Multiple Followers
  - shows that a channel may be linked to multiple followers (e.g., channel ch2 followed by f1 and f2), whereas each follower may be linked to multiple channels (e.g., f2 follows ch1 and ch2).
![4 2](https://user-images.githubusercontent.com/90284881/148714802-2d8a9d7b-3ffd-4485-9768-1d230c8ef5c3.png)

