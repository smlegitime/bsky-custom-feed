# bsky-custom-feed
Creating an accessible feed generator on top of Bluesky.

## Existing tools
[Bluesky Feed Creator](https://blueskyfeedcreator.com/) 
- Pros: Offers a variety of features, including custom moderation rules and an analytics dashboard.
- Cons: Priced, BUT has a free tier. [Pricing details](https://blueskyfeedcreator.com/pricing)

## Possible enhancements 🤷🏾‍♀️
- Auto moderator: YAML generator for auto moderation rules
- Multiple languages support

## Requirements
Definition of the system from the user's perspective. 
- Audience: Bluesky users. Includes non-technical and technical members.
- Description: Bluesky users wish to more easily create feed generators. They want a simple UI that enables them to create and monitor a custom feed without needing technical knowledge. Do they have any needs that the Bluesky feed creator cannot provide (e.g., price, native/web)?

## Specs
Main commands
- **Create**: Labeler converts a series of prompts (chat model) into a feed generator. Would have to be more of a chatbot to include all feed generator properties (shortname, public info, search terms
- **Validate**: Should render a sample feed view for validation and customization
- **Launch**: Publish the feed to Bluesky
- **Manage**: User can see feed activity in real time, and manage feed content and settings on a portal. Will incur hosting and storage costs for firehose and appview data (?)

## Potential User Interface
- Web UI? ([Streamlit](https://streamlit.io/) or sample [TS project](https://backroad.sudomakes.art/)?)
- Native UI? ([React Native](https://reactnative.dev/) or [Flutter](https://flutter.dev/))
- Mobile? (See links for native UI)
  
## Documentation
- [Custom feed documentation](https://docs.bsky.app/docs/starter-templates/custom-feeds)
- [LangGraph.js](https://github.com/bluesky-social/feed-generator)
  
## Possible Tech Stacks
- [TypeScript](https://github.com/bluesky-social/feed-generator) + LangGraph.js
- [Python](https://github.com/MarshalX/bluesky-feed-generator) + LangGraph
